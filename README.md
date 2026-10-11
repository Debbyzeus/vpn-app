# DEBBYZEUS VPN Android App

This repository contains a minimal Android app that loads your existing VPN dashboard HTML inside a WebView so it can be packaged as an APK.

## Included
- Android project scaffold
- WebView app shell
- Local asset version of your HTML UI
- Internet permission setup

## How to build the APK
1. Install Android Studio.
2. Open this folder as an Android project.
3. Let Gradle sync.
4. Build > Generate Signed Bundle / APK.
5. Choose APK and build.

## Files of interest
- `app/src/main/assets/index.html` — your dashboard HTML
- `app/src/main/java/com/debbyzeus/vpnapp/MainActivity.kt` — WebView container
- `app/src/main/AndroidManifest.xml` — app permissions and activity config

## Notes
This version wraps your design in a WebView, which is the fastest route to turning your current HTML mockup into a working Android APK.

If you want a more native Android experience later, we can convert the interface to Kotlin views and Material components.
