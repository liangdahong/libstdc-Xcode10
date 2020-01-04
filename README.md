# 处理 Xcode10+ 以下库引起的相关问题 

```
libstdc++.dylib
libstdc++.6.tbd
libstdc++.6.dylib
libstdc++.6.0.9.tbd
libstdc++.6.0.9.dylib

```

## 模拟器

- 把 `模拟器`文件夹下的 6 个文件拷贝到如下其中一个路径下，可能由 Xcode 版本不同而不同。

```
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/

/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator.sdk/usr/lib/
```



## 真机

- 把 `真机`文件夹下的 2 个文件拷贝到如下路径下。

```
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/usr/lib/
```











