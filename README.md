# Chronova — Smart Calendar

Chronova Android wrapper built with Capacitor.

## Build APK
GitHub Actions runs on every push to `main` and can also be started manually from Actions → Build Chronova Android APK.

The current workflow produces a **debug APK** artifact. Android may show the normal unknown-source installation prompt. This does not bypass Play Protect.

## Notes
- Main web app: `www/index.html`
- Capacitor app ID: `com.shavan.chronova`
- Data in the web app is stored locally in WebView storage. Export JSON backups periodically.
- The app's current reminders are in-app checks; they are not guaranteed Android background notifications.
