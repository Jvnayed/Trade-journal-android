TRADE JOURNAL — ANDROID PROJECT

This is an Android Studio project wrapping your supplied HTML Trade Journal in an Android WebView.
It keeps the original interface and trading features. The Google Fonts network import was removed so
that the app does not need an internet connection to load. A system sans-serif font is used instead.

BUILD THE APK
1. Install Android Studio on a computer.
2. Extract this ZIP file.
3. In Android Studio choose Open, then select the extracted trade-journal-android folder.
4. Allow Android Studio to install/sync the required Android Gradle plugin and SDK (API 35).
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. When the build finishes, choose Locate. The APK is normally at:
   app/build/outputs/apk/debug/app-debug.apk
7. Transfer that APK to your Android phone and install it. Android may ask you to allow installs
   from that file manager/browser.

DATA AND PRIVACY
- Trade entries are stored in the app's local WebView storage on the device.
- The app does not require an account or send trades to a server.
- Uninstalling the app or clearing its app data may erase saved trades.
- Use a separate backup/export process before changing phones; this original HTML app has no
  built-in export/import feature.
- Images and videos are stored as data URLs in local storage, so large attachments can fill storage.

PACKAGE
Application ID: com.rookstone.tradejournal
App name: Trade Journal
Version: 1.0
Minimum Android: 6.0 (API 23)
