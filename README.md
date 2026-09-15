# PhotoDoc Pro

PhotoDoc Pro is a mobile-focused photo, document scanning, ID-photo and PDF utility web app.

## Current project

- Mobile-first single-page web app
- Camera/gallery based document and photo workflows
- PDF creation and reading tools
- Local browser storage for saved files/settings
- PWA manifest and app icons
- Privacy Policy page

## Run locally

Because this project loads PDF libraries from a CDN, run it through a local web server rather than opening `index.html` directly.

For example, with Python:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080/`.

## GitHub Pages

This is a static web project and can be published with GitHub Pages. In the repository settings, enable Pages for the branch/folder containing these files.

## Android / AdMob / Play Store roadmap

1. Validate and test the web app.
2. Package the web app as an Android application (for example, with Capacitor).
3. Add Google Mobile Ads SDK/AdMob to the Android project only when ready.
4. Update the Privacy Policy and Google Play Data Safety information to match the final SDK/configuration.
5. Build and sign an Android App Bundle (AAB).
6. Test through Google Play testing tracks before production release.

Do not commit AdMob app IDs, API keys, signing keys, or other secrets to this repository.
