# Petrol Pump Dashboard — Android WebView App

This Android project wraps the Streamlit dashboard:

https://ph6r32wmq2vq7qqidnmql8.streamlit.app/

## Build with Android Studio

1. Install the latest Android Studio.
2. Open this folder as a project.
3. Let Gradle sync.
4. Connect an Android phone with USB debugging enabled, or create an emulator.
5. Run the `app` configuration.
6. To create an APK: **Build → Generate App Bundles or APKs → Generate APKs**.
7. The debug APK will normally be under:
   `app/build/outputs/apk/debug/app-debug.apk`

## Important

The Streamlit URL must be accessible without a login for a simple kiosk-style app.
If the Streamlit deployment requires authentication, the WebView will show the authentication flow and the app may require the user to sign in.

The dashboard itself remains hosted by Streamlit; this Android app is only the mobile wrapper.
