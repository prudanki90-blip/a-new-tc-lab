# Daniels TC Lab

Android packaging project for Daniels Tissue Culture Lab.

## Application details

- App name: Daniels TC Lab
- Android application ID: com.danielstclab.app
- Framework: Capacitor 7
- Web application: www/index.html

## Original application

The original HTML application is stored at:

`www/index.html`

Its existing HTML, CSS and JavaScript are preserved. The Android wrapper loads this file through Capacitor.

## Building the APK

The project uses GitHub Actions to build the Android application.

1. Open the repository's Actions tab.
2. Select Build Daniels TC Lab APK.
3. Select Run workflow.
4. Choose the main branch.
5. Click Run workflow.

Wait for the workflow to finish successfully.

## Downloading the APK

1. Open the completed workflow run.
2. Find the Artifacts section.
3. Download `Daniels-TC-Lab-debug-apk`.
4. Extract the ZIP to obtain `app-debug.apk`.

## Important

This is a debug APK for testing.

Test the application on an Android device before considering the packaging complete. Check data persistence, file import and export, external resources, printing and the main application features.
