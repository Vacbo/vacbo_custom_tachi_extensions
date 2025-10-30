# Vacbo Custom Extensions

Custom Tachiyomi/Keiyoushi extensions repository with enhanced features.

## Installation

Add this repository to your Keiyoushi/Mihon app:

**Repository URL:**
```
https://raw.githubusercontent.com/Vacbo/vacbo_custom_tachi_extensions/refs/heads/main/repo/index.min.json
```

### Steps:
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
  - ✅ WebView login for authentication
  - ✅ Cookie/token paste authentication (alternative)
  - ✅ Premium/early chapter access for authenticated users
  - ✅ High-resolution image support with automatic fallback
  - ✅ Session management with automatic expiry detection

#### Authentication Methods

**WebView Login (Recommended)**:
1. Go to Extension Settings → Asura Scans
2. Select "Authentication method" → "WebView login"
3. Tap "Launch WebView login"
4. Log in through the embedded browser
5. Press back when done

**Cookie Paste (Alternative)**:
1. Go to Extension Settings → Asura Scans
2. Select "Authentication method" → "Paste cookie or token"
3. Copy cookies from browser DevTools (or Bearer token)
4. Paste into "Paste cookie or token" field

#### Premium Chapters

- When **authenticated**: Premium chapters are visible and accessible
- When **unauthenticated**: Premium chapters are hidden by default (can be toggled in settings)

#### High-Resolution Images

- Enable "Force high quality chapter images" in settings
- Automatically falls back to standard quality if hi-res unavailable
- Increases bandwidth by ~50% when enabled

## Repository Information

- **Maintainer**: Vacbo
- **Structure**: Follows [keiyoushi/extensions](https://github.com/keiyoushi/extensions) format
- **Updates**: Automatic updates when new versions are published

## Issues & Support

Report issues or request features through the repository issues page.

## License

Extensions follow the original source licensing. This repository is for distribution only.

