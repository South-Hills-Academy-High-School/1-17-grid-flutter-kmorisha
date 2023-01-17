# 1-17-grid_flutter

Once you have cloned the repository, open a terminal in Visual Studio code and run this command (including the . at the end):

    flutter create --project-name grid_flutter .

Example:

    user@MacBook-Air ~ % flutter create --project-name grid_flutter .

Press `enter` and you will see Flutter run a bunch of commands:

    Recreating project ....
    test\widget_test.dart (created)
    .idea\libraries\Dart_SDK.xml (created)
    .idea\libraries\KotlinJavaRuntime.xml (created)
    .idea\modules.xml (created)
    .idea\runConfigurations\main_dart.xml (created)
    .idea\workspace.xml (created)
    android\app\build.gradle (created)
    android\app\src\main\kotlin\com\example\wordpair_flutter\MainActivity.kt (created)
    android\build.gradle (created)
    android\wordpair_flutter_android.iml (created)
    android\.gitignore (created)
    android\app\src\debug\AndroidManifest.xml (created)
    android\app\src\main\AndroidManifest.xml (created)
    android\app\src\main\res\drawable\launch_background.xml (created)
    android\app\src\main\res\drawable-v21\launch_background.xml (created)
    android\app\src\main\res\mipmap-hdpi\ic_launcher.png (created)
    android\app\src\main\res\mipmap-mdpi\ic_launcher.png (created)
    android\app\src\main\res\mipmap-xhdpi\ic_launcher.png (created)
    android\app\src\main\res\mipmap-xxhdpi\ic_launcher.png (created)
    android\app\src\main\res\mipmap-xxxhdpi\ic_launcher.png (created)
    android\app\src\main\res\values\styles.xml (created)
    android\app\src\main\res\values-night\styles.xml (created)
    android\app\src\profile\AndroidManifest.xml (created)
    android\gradle\wrapper\gradle-wrapper.properties (created)
    android\gradle.properties (created)
    android\settings.gradle (created)
    ios\Runner\AppDelegate.swift (created)
    ios\Runner\Runner-Bridging-Header.h (created)
    ios\Runner.xcodeproj\project.pbxproj (created)
    ios\Runner.xcodeproj\xcshareddata\xcschemes\Runner.xcscheme (created)
    ios\.gitignore (created)
    ios\Flutter\AppFrameworkInfo.plist (created)
    ios\Flutter\Debug.xcconfig (created)
    ios\Flutter\Release.xcconfig (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Contents.json (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-1024x1024@1x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@1x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@2x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@3x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@1x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@2x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@3x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@1x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@2x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@3x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-60x60@2x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-60x60@3x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-76x76@1x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-76x76@2x.png (created)
    ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-83.5x83.5@2x.png (created)
    ios\Runner\Assets.xcassets\LaunchImage.imageset\Contents.json (created)
    ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage.png (created)
    ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage@2x.png (created)
    ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage@3x.png (created)
    ios\Runner\Assets.xcassets\LaunchImage.imageset\README.md (created)
    ios\Runner\Base.lproj\LaunchScreen.storyboard (created)
    ios\Runner\Base.lproj\Main.storyboard (created)
    ios\Runner\Info.plist (created)
    ios\Runner.xcodeproj\project.xcworkspace\contents.xcworkspacedata (created)
    ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
    ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings (created)
    ios\Runner.xcworkspace\contents.xcworkspacedata (created)
    ios\Runner.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
    ios\Runner.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings (created)
    linux\.gitignore (created)
    linux\CMakeLists.txt (created)
    linux\flutter\CMakeLists.txt (created)
    linux\main.cc (created)
    linux\my_application.cc (created)
    linux\my_application.h (created)
    macos\.gitignore (created)
    macos\Flutter\Flutter-Debug.xcconfig (created)
    macos\Flutter\Flutter-Release.xcconfig (created)
    macos\Runner\AppDelegate.swift (created)
    macos\Runner\Assets.xcassets\AppIcon.appiconset\app_icon_1024.png (created)
    macos\Runner\Assets.xcassets\AppIcon.appiconset\app_icon_128.png (created)
    macos\Runner\Assets.xcassets\AppIcon.appiconset\app_icon_16.png (created)
    macos\Runner\Assets.xcassets\AppIcon.appiconset\app_icon_256.png (created)
    macos\Runner\Assets.xcassets\AppIcon.appiconset\app_icon_32.png (created)
    macos\Runner\Assets.xcassets\AppIcon.appiconset\app_icon_512.png (created)
    macos\Runner\Assets.xcassets\AppIcon.appiconset\app_icon_64.png (created)
    macos\Runner\Assets.xcassets\AppIcon.appiconset\Contents.json (created)
    macos\Runner\Base.lproj\MainMenu.xib (created)
    macos\Runner\Configs\AppInfo.xcconfig (created)
    macos\Runner\Configs\Debug.xcconfig (created)
    macos\Runner\Configs\Release.xcconfig (created)
    macos\Runner\Configs\Warnings.xcconfig (created)
    macos\Runner\DebugProfile.entitlements (created)
    macos\Runner\Info.plist (created)
    macos\Runner\MainFlutterWindow.swift (created)
    macos\Runner\Release.entitlements (created)
    macos\Runner.xcodeproj\project.pbxproj (created)
    macos\Runner.xcodeproj\project.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
    macos\Runner.xcodeproj\xcshareddata\xcschemes\Runner.xcscheme (created)
    macos\Runner.xcworkspace\contents.xcworkspacedata (created)
    macos\Runner.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
    wordpair_flutter.iml (created)
    web\favicon.png (created)
    web\icons\Icon-192.png (created)
    web\icons\Icon-512.png (created)
    web\icons\Icon-maskable-192.png (created)
    web\icons\Icon-maskable-512.png (created)
    web\index.html (created)
    web\manifest.json (created)
    windows\.gitignore (created)
    windows\CMakeLists.txt (created)
    windows\flutter\CMakeLists.txt (created)
    windows\runner\CMakeLists.txt (created)
    windows\runner\flutter_window.cpp (created)
    windows\runner\flutter_window.h (created)
    windows\runner\main.cpp (created)
    windows\runner\resource.h (created)
    windows\runner\resources\app_icon.ico (created)
    windows\runner\runner.exe.manifest (created)
    windows\runner\Runner.rc (created)
    windows\runner\utils.cpp (created)
    windows\runner\utils.h (created)
    windows\runner\win32_window.cpp (created)
    windows\runner\win32_window.h (created)
    Running "flutter pub get" in namer_app...                        2,010ms
    Wrote 122 files.

    All done!
    In order to run your application, type:

    $ cd .
    $ flutter run

    Your application code is in .\lib\main.dart.
