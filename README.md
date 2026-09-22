# Face Scan Store

Android camera app that captures face photos and stores them in the app's private storage.

## Features

- Camera preview
- **Scan & Store Face** button
- Stores captured JPEG files under the app-private `files/faces` directory
- Lists stored scan filenames
- No network permission
- No server upload
- No biometric face recognition or person identification

## Automatic APK build

Every push to `main` starts GitHub Actions. The workflow builds a debug APK and uploads:

`FaceScanStore-debug-apk`

The APK file is:

`app/build/outputs/apk/debug/app-debug.apk`

## Android project

- Package: `com.zabed.facescanstore`
- Min SDK: 23
- Target SDK: 36
- Java/Kotlin JVM target: 17
