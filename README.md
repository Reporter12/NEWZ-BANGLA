# Newz Bangla Android app

A simple Android WebView app for https://www.newzbangla.com/.

## Build an APK using GitHub Actions (no Android Studio required)

1. Create a new **private or public** GitHub repository.
2. Upload the contents of this ZIP to the repository (keep the `.github` folder).
3. Open the repository's **Actions** tab.
4. Select **Build Newz Bangla APK** and click **Run workflow**.
5. When the workflow finishes, open that run and download the **Newz-Bangla-APK** artifact.
6. Extract the downloaded artifact ZIP. It contains `app-debug.apk`.

## Build locally with Android Studio

Open this folder as an Android Studio project, allow Gradle sync, then choose
**Build > Build Bundle(s) / APK(s) > Build APK(s)**.

## App details

- App name: Newz Bangla
- Package: `com.newzbangla.app`
- Website: `https://www.newzbangla.com/`
- External links open in the phone's browser.
- Android minimum version: Android 6.0 (API 23).

This is an unsigned debug APK for testing and direct installation. For Play Store
publishing, create a release build and sign it with your own private upload key.
