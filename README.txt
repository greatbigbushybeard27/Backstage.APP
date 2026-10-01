# AV Tracker PWA

This is the installable web-app version of AV Tracker.

## Important
The QR camera scanner requires the app to be served over HTTPS. Opening `index.html` directly from Downloads will not give Chrome the camera permissions it needs.

## Publish
Upload all four files to a static HTTPS host:
- index.html
- manifest.webmanifest
- sw.js
- icon.svg

GitHub Pages and Cloudflare Pages both work.

Then open the HTTPS address on Android Chrome and choose:
Chrome menu (⋮) -> Add to Home screen -> Install.

Your equipment/job data remains in the browser's local storage in this version.
