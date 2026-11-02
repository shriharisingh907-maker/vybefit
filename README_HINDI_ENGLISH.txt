# VYBEFIT PWA starter

This is a Progressive Web App starter based on the VYBEFIT demo.

## Publish free with GitHub Pages
1. Sign in to GitHub and create a new **public** repository named `vybefit`.
2. Upload every file and folder from this package (keep `index.html`, `manifest.webmanifest`, `sw.js`, and `icons/` at the repository root).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for the Pages URL shown there, then open it in Chrome on Android.

## Install on Android
1. Open the published HTTPS website in Chrome.
2. Tap the three-dot menu.
3. Choose **Install app** or **Add to Home screen**.
4. Confirm. VYBEFIT will open in an app-like full-screen window.

## Android APK
This package is a PWA website, not a signed APK. After the website is published over HTTPS, use PWABuilder (https://www.pwabuilder.com/) to package the URL as an Android app. Review package details and signing carefully. Keep signing keys private.

## Important demo limitations
- Member data is stored only in the current browser/device (localStorage); it is not synced between phones.
- QR camera scanning, real user accounts, cloud database, online payments and automatic recurring billing are not connected.
- Do not use real member personal/payment data until secure login, server-side database, access controls, backups and privacy notices are implemented.
- Renewal button records a demo renewal; it does not charge money or activate autopay.
