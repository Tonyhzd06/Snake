# 滑动贪吃蛇（Android）

一个原生 Android 简易贪吃蛇游戏：上下左右滑动改变方向，吃果实加分，撞墙或撞到自己就结束，点按可重新开始。

## 生成 APK
本环境没有安装 Android SDK / Gradle，因此无法在这里直接编译出可安装 APK。可以用 Android Studio 打开本文件夹并构建：

1. 安装 Android Studio（包含 Android SDK）。
2. 选择 **Open**，打开 `SwipeSnakeAndroid` 文件夹。
3. 等待 Gradle Sync；如提示安装 Android SDK 35，请同意安装。
4. 选择 **Build → Build Bundle(s) / APK(s) → Build APK(s)**。
5. APK 通常生成在 `app/build/outputs/apk/debug/app-debug.apk`。

也可在安装好 Android SDK 和 Gradle 的环境中，在项目目录运行 `gradle assembleDebug`。
