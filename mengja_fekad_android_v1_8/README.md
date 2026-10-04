# መንጃ ፈቃድ ፈተና — Android wrapper v1.8

This project wraps the current mobile web app in a native Android WebView.

- Package: `com.mengjafekad.app`
- Target API: 36
- Min API: 23
- Version: 1.8
- Main app content: `app/src/main/assets/index.html`
- Build: GitHub Actions workflow in `.github/workflows/android.yml`

The current engine lesson photos include some Wikimedia Commons remote URLs, so those specific images require internet access until the image assets are bundled locally.

This is a debug/test build stage. AdMob and Google Play publishing are deliberately not added yet.
