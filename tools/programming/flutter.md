## Flutter

Flutter 是 Google 开发的 UI 工具包，可以帮助开发者使用一套代码库，为移动、Web、桌面和嵌入式设备构建高性能、高保真的应用程序。

### 环境搭建

1.  **下载 Flutter SDK**：
    *   访问 [Flutter 官网](https://flutter.dev) 或 [GitHub Releases](https://github.com/flutter/flutter/releases) 下载最新稳定版 SDK。
    *   解压到你喜欢的目录，例如 `~/development/flutter`。

2.  **配置环境变量**：
    *   将 Flutter 的 `bin` 目录添加到你的系统 `PATH` 中。
    *   **Mac/Linux**：编辑 `~/.zshrc` 或 `~/.bashrc` 文件，添加：
        ```bash
        export PATH="$PATH:~/development/flutter/bin"
        ```
        然后运行 `source ~/.zshrc` (或 `source ~/.bashrc`) 使其生效。
    *   **Windows**：在系统环境变量中添加 `C:\development\flutter\bin`。

3.  **设置国内镜像 (可选，强烈推荐)**：
    *   由于网络问题，直接访问 Flutter 官方仓库可能较慢。可以设置国内镜像。
    *   **Mac/Linux**：在 `~/.zshrc` 或 `~/.bashrc` 中添加：
        ```bash
        export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn
        export PUB_HOSTED_URL=https://pub.flutter-io.cn
        ```
        同样需要 `source` 命令使其生效。
    *   **Windows**：在系统环境变量中添加以上两个变量。

4.  **安装依赖**：
    *   **Android**：需要安装 Android Studio 并配置 Android SDK、SDK Platform-Tools, SDK Build-Tools, Android SDK Manager, Android Virtual Device Manager。确保 ANDROID_HOME 环境变量已设置。
    *   **iOS**：需要安装 Xcode。

5.  **安装编辑器插件**：
    *   在你的 IDE (如 VS Code 或 Android Studio) 中安装 Dart 和 Flutter 插件。

6.  **验证安装**：
    *   打开终端或命令行，运行 `flutter doctor`。它会检查你的环境并报告任何缺失的依赖项。

7.  **创建新项目**：
    *   运行 `flutter create my_app` (将 `my_app` 替换为你自己的项目名)。
    *   进入项目目录 `cd my_app`。
    *   运行 `flutter run` 启动应用。

更多详情请参考 [Flutter 官方文档](https://docs.flutter.dev/get-started/install)。