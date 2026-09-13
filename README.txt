SORCERY BOX MODS - ANDROID APP PROJECT

This project creates a normal Android APK named Sorcery Box Mods.
The app opens the supplied Lovable project inside its own app window, not Chrome.

IMPORTANT:
The website uses WebUSB/WebADB for direct USB device control. Android WebView does
not expose the browser WebUSB API, so the wrapped app may not be able to perform
direct USB ADB operations even though the website UI opens as an app.

To build:
1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Build > Build APK(s).
4. Install the resulting app-debug.apk with Android Package Installer.
