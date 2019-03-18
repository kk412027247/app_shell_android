# 安卓app外壳
[参考地址](https://jerrynest.io/app-android-webview/)



修改主活动 中 `webview.loadUrl("https://www.jianshu.com/");` 的地址即可。

## app打包
```
$ ./gradlew assembleRelease
```


## 加载本地文件

替换 src/main/assets 文件夹中的文件即可

## 输入文件目录

/Users/assetfun/source/app_shell/app_shell_android/app/build/outputs/apk/release/app-release.apk

## 命令行安装app

adb install /Users/assetfun/source/app_shell/app_shell_android/app/build/outputs/apk/release/app-release.apk