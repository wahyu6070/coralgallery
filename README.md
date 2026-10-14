# Coral Gallery

**A simple, private photo & video gallery for Android — with a built-in editor and player.**

Coral Gallery is a clean, modern gallery built with Kotlin, Jetpack Compose and
Material 3 (dynamic color / Material You on Android 12+). It does one thing well:
browsing, viewing, editing and playing the media already on your device — fast,
offline, and free of clutter.

> This repository hosts **release builds (APK)** only. Grab the latest version from
> the [**Releases**](https://github.com/wahyu6070/coralgallery/releases/latest) page.

## Download

| | |
|---|---|
| Latest release | [Releases → latest](https://github.com/wahyu6070/coralgallery/releases/latest) |
| Package name | `com.coralgallery` |
| Requires | Android 8.0 (API 26) or newer |
| Size | ~3 MB |

1. Download `CoralGallery-v<version>.apk` from the latest release.
2. Open it on your phone and allow *Install unknown apps* for your browser / file manager when asked.
3. Launch **Gallery** and grant storage access on first start.

## Features

**Gallery**
- Photos tab with a smooth, timeline-style grid of everything on your device
- Folders tab to browse by album
- Multi-select for quick batch delete and share
- Fast scanning via Android's MediaStore, with cached thumbnails

**Photo viewer**
- Pinch-to-zoom, pan, and swipe between photos
- Jump straight into the editor from the viewer

**Photo editor**
- Crop and rotate
- Brush, text, emoji and stickers
- Filters

**Video player**
- Smooth playback powered by Media3 / ExoPlayer
- Full-screen player with gesture controls

**Design**
- Material 3 with dynamic color on Android 12+
- Light, dark, or follow-system theme
- Shows up in *Open with* for images and videos from other apps

**Languages:** English, Indonesian, Arabic, Japanese, Russian, Chinese.

## Privacy

- Works fully offline — the app has **no internet permission**
- No ads, no analytics, no trackers, no accounts
- Your photos and videos never leave your device

### Permissions

| Permission | Why |
|---|---|
| All files access (`MANAGE_EXTERNAL_STORAGE`, Android 11+) | Find, open, and delete your photos & videos in any folder |
| `READ_EXTERNAL_STORAGE` (Android 10 and below) | Same, on older Android versions |

## Verifying the APK

Release APKs are signed with the following certificate:

```
SHA-256: 70:20:70:CD:12:40:F9:63:87:8A:7C:9C:B6:E3:BA:A6:C6:04:00:3E:2D:BC:A5:F4:B7:94:5F:1F:39:03:12:60
```

Check with `apksigner verify --print-certs CoralGallery-v<version>.apk`. Each release
also lists the APK's own SHA-256 checksum in its notes.

> Note: builds from the Google Play Store are signed by Google Play and cannot be
> updated in place with an APK from this page (or vice versa). Uninstall first if you
> want to switch.

## License

Coral Gallery is released under the [MIT License](LICENSE).
Third-party open-source libraries used in the app remain under their own licenses.
