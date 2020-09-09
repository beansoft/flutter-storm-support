# 🧩FluterStorm (former Flutter Storm)
Unofficial WebStorm/PhpStorm/GoLand/PyCharm/CLion/RubyMine plugin for developing Flutter applications.

![Downloads](https://img.shields.io/jetbrains/plugin/d/14718) ![Rating](https://img.shields.io/jetbrains/plugin/r/rating/14718)
![Version](https://img.shields.io/jetbrains/plugin/v/14718) ![Vistor](https://visitor-badge.glitch.me/badge?page_id=14718)

Flutter and the related logo are trademarks of Google LLC. We are not endorsed by or affiliated with Google LLC.

Made with ❤️ by BeanSoft.

[✅]CLion, GoLand, IntelliJ IDEA Ultimate, IntelliJ IDEA Educational, PhpStorm,RubyMine, WebStorm, PyCharm - fully supported
[🚸]Rider - supports open project folder and edit, run, debug, can't create new project, I'm still working on the solution.
[❌] - AppCoder -can't open project folder, can create new project
[Features](https://plugins.jetbrains.com/plugin/14718-fluterstorm/features) | [FAQ](https://plugins.jetbrains.com/plugin/14718-fluterstorm/faq)
For students and teachers this plugin is Free - Students and academic staff members are eligible to use this plugin free, upon verification of their university/college domain email. Please using your domain mail send request to me, I'll give send you a one year free subscription code.

Plugin home page: https://plugins.jetbrains.com/plugin/14718-fl-storm

## Installation

- Using IDE built-in plugin system:

  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "FluterStorm"</kbd> >
  <kbd>Install Plugin</kbd>

- Manually:

  Download the [latest release](https://plugins.jetbrains.com/plugin/14718-fl-storm/versions) and install it manually using
  <kbd>Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>


## 安装

- IDE 内建插件市场:
  
  <kbd>Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>搜索 "FluterStorm"</kbd> >
  <kbd>Install Plugin</kbd>
  
- 手动:

  点击 [latest release](https://plugins.jetbrains.com/plugin/14718-fl-storm/versions) , 点击最新版 `*.zip`文件并下载，而后进入 IDE 
  <kbd>Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd> 安装.

[Features](https://plugins.jetbrains.com/plugin/14718-fl-storm/features) | [FAQ](https://plugins.jetbrains.com/plugin/14718-fl-storm/faq)

Based on official [Flutter plugin](https://plugins.jetbrains.com/plugin/9212-flutter) with bugs fix and support for *Storm IDE(IDEA, Android Studio might be supported). Also provides a tool window for one-click run flutter commands and some other features.


Support for developing Flutter applications. Flutter gives developers an easy and productive way to build and deploy cross-platform, high-performance mobile apps for both Android and iOS. Installing this plugin will also need install the Dart plugin to enables Flutter specific functionality.



WANING: Please uninstall Official Flutter plugin before installing this plugin, there might be conflicts.
Or uninstall FluterStorm before you installing the Official Flutter plugin to ensure stability.

## Features

- Flutter official IDE features like code edit, refactor, run, debug, hot reload, hot restart; Flutter performance, outline inspector
- Create New Flutter project on *Storm IDE
- Fix UI freeze when creating New Flutter project on *Storm IDE and IDEA/Ultimate
- Visual color editor for Color.fromARGB and Color.fromRGBO
- Single click in pubspec.yaml and Dart source code to open dependency package's source file or view homepage in web browser
- Preview Image.asset('images/ble.png') icon as editor line marker and click to open
- Auto complete of font name and image path when edit Dart string
- Autocomplete Pub Packages in pubspec.yaml
- Highlight and Update Pub Packages in pubspec.yaml
- View Pub Package's Documentation in pubspec.yam, press `Ctrl+Q` to show additional information
- Preview project images as an icon in your project explorer, supports png, svg, jpg, etc
- Debug Android devices over wifi with just one click
- Display colorful terminal output
- Start Xcode, Android Studio on Mac with one click
- list and run android emulator(avd)
- list all iOS simulator, start device and run as target
- take screenshot
- Flutter Pub Get
- Flutter Pub Upgrade
- Flutter Pub Outdated
- Flutter Logs
- Flutter test
- flutter upgrade
- fultter build ios and android
- fultter clean
- Reveal project folder in Finder/Explorer
- Generate Widgets: When creating a new file, choose the *"New Flutter Widget"* option.
- Generate Blocs: When creating a new file, choose the *"New Flutter Bloc"* option.

**Some Features provieded by FluterStorm but now in the offcial Flutter Plugin**

- Color editor
  ![img](https://plugins.jetbrains.com/files/14718/screenshot_23035.png)

- Preview project images as an icon in your project explorer, supports png, svg, jpg, etc

![Screenshot 1](https://plugins.jetbrains.com/files/14718/screenshot_22957.png)

- Single click in pubspec.yaml and Dart source code to open dependency package's homepage in web browser(since 2020.2.2)

![img](https://plugins.jetbrains.com/files/14718/screenshot_22901.png) ![img](https://plugins.jetbrains.com/files/14718/screenshot_22902.png)

- Debug Android devices over wifi with just one click(since 2020.2.0) ![img](https://plugins.jetbrains.com/files/14718/screenshot_22836.png)

## Installation

First, please setup your Flutter dev env: https://flutter.dev/docs/get-started/install, Then install this plugin to your IDE, then you will find a Flutter Storm toolbar. Follow the guide to install the Dart plugin to adds Dart and enables Flutter specific functionality.

#FAQ

# How to fix KOTLIN_BUNDLED error when open project in WebStorm?

After create the project, and opened, the WebStorm will report an issue:

```
Load error: undefined path variables
KOTLIN_BUNDLED is undefined. Fix it
Path variables are used to substitute absolute paths in WebStorm project files and allow project file sharing in version control systems.
Some of the files describing the current project settings contain unknown path variables and WebStorm cannot restore those paths.
```
To fix it, just click the **Fix it** link, enter the value as follows:
```
Windows:
C:\Program Files\Android Studio\plugins\Kotlin\kotlinc
Mac:
/Applications/Android Studio.app/Contents/plugins/Kotlin/kotlinc
```
See screenshot:
![](https://plugins.jetbrains.com/files/14718/159-page/image61.png)
![](https://plugins.jetbrains.com/files/14718/159-page/image60.png)



[中文文档 Chinese Documentation](https://www.cnblogs.com/beansoft/p/flutter_storm.html)
