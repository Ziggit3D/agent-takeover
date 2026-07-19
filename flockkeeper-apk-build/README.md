# Flockkeeper Android test build

A local-first Android wrapper for the full Flockkeeper HTML application.

## Test-build behaviour

- Installs as a normal Android app.
- Records persist in the app's private WebView storage after closing or restarting.
- Works offline.
- Photos can be selected from the phone or captured with the camera chooser.
- JSON and CSV exports are written to `Downloads/Flockkeeper`.
- Uninstalling the app or clearing its app data removes local records, so regular JSON backup exports remain important.

This debug APK is for private testing and is signed using Android's generated debug key. A production release needs a permanent private signing key, privacy documentation, versioning and store packaging.
