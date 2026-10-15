# Life Goal Investment — Android app

A lightweight Android WebView wrapper for the existing Life Goal Investment website. It uses the same website and backend; it does not create a separate account system or trading engine.

## Website
https://lifegoalinvestment.lovable.app

## Build an APK
Every push to `main` runs the **Build Android APK** GitHub Actions workflow. You can also run it manually from the Actions tab using **Run workflow**.

When the workflow succeeds:
1. Open the repository's **Actions** tab.
2. Open the latest **Build Android APK** run.
3. Download the `life-goal-investment-android-apk` artifact.
4. Extract it to get `app-debug.apk`.

The artifact is a debug APK for testing and direct installation. Android may ask the user to allow installation from the browser or file manager used to open it.

## Notes
- Requires Android 7.0 (API 24) or newer.
- The app loads the live website, so website changes appear when the app reloads.
- Internet access is required.
- This repository contains the Android wrapper only, not the private website source.
- This first version has not been signed as a production release.
