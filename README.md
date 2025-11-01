# Vacbo Custom Extensions

Custom Tachiyomi/Keiyoushi extensions repository with enhanced features.

## Installation

Add this repository to your Keiyoushi/Mihon app:

**Repository URL:**

```text
https://raw.githubusercontent.com/Vacbo/vacbo_custom_tachi_extensions/main/index.min.json
```

### Steps

1. Open Keiyoushi/Mihon
2. Go to **Settings** → **Extension** → **Extension Repositories**
3. Tap **Add** (+ icon)
4. Paste the repository URL above
5. Tap **Add**
6. Browse to **Browse** → **Extensions**
7. Install **Asura Scans** from this repository

## Extensions

### Asura Scans

- **Language**: English
- **Version**: 1.4.49
- **Features**:
  - ✅ Automatic WebView cookie synchronization (cross-platform compatible)
  - ✅ Custom CookieJar for seamless authentication
  - ✅ Premium/early chapter access (Asura+ Premium)
  - ✅ Max quality images (Asura+ Basic/Premium)
  - ✅ Automatic fallback for missing max quality images
  - ✅ Session expiry detection and handling

#### Authentication

#### WebView Login (automatic cookie sync)

1. Login via WebView in the app
2. Navigate to `https://asuracomic.net` and sign in
3. Cookies sync automatically via CookieJar - no manual steps required

#### Subscription tiers

- **Asura+ Basic**: Max quality images + ad-free experience
- **Asura+ Premium**: Early access chapters + all Basic benefits

#### Premium Chapters

- When **authenticated**: Premium chapters are visible and accessible
- When **unauthenticated**: Premium chapters are hidden by default (can be toggled in settings)

#### Max Quality Images

- Enable "Enable max quality" in settings
- Requires Asura+ Basic/Premium subscription
- Automatically falls back to standard quality if max quality unavailable
- Increases bandwidth by ~50% when enabled

## Repository Information

- **Maintainer**: Vacbo
- **Structure**: Follows [keiyoushi/extensions](https://github.com/keiyoushi/extensions) format
- **Updates**: Automatic updates when new versions are published

## Issues & Support

Report issues or request features through the repository issues page.

## License

Extensions follow the original source licensing. This repository is for distribution only.
