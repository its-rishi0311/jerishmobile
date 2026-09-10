JERISH MOBILE - ANDROID APP

This project wraps your existing jerish2.html website in a mobile Android WebView.

FEATURES
- Phone-sized full-screen layout
- JavaScript enabled
- localStorage/DOM storage enabled
- Internet permission for Firebase
- Existing Firebase JavaScript integration remains in the HTML
- Android back button navigates the web app first

HOW TO BUILD THE APK
1. Install Android Studio.
2. Open this entire "JerishMobileApp" folder in Android Studio.
3. Allow Gradle to sync/download the Android Gradle Plugin and SDK.
4. Connect an Android phone or use an emulator.
5. Choose Build > Build APK(s).
6. The debug APK will be under:
   app/build/outputs/apk/debug/app-debug.apk

IMPORTANT
The HTML uses Firebase over the internet, so the app needs an internet connection
for cloud customer accounts, chat, jobs, and complaints.

Your Firebase Realtime Database rules must permit the operations your HTML uses.
