# VisuBoard

![VisuBoard Logo](icon.png)

**Unbelievably simple digital signage — on any screen.** VisuBoard turns any display into a fullscreen, auto-playing showcase for your images and videos. No cables, no subscriptions, no complicated setup. Import your media, add your logo, and let it run.

Grab the latest release for your platform below.

## Download

➡️ **[Download the latest release](../../releases/latest)**

| Platform | File |
|----------|------|
| 🤖 Android | `.apk` |
| 🪟 Windows | `.exe` |
| 🍎 macOS (Apple Silicon) | `-arm64.dmg` |
| 🍎 macOS (Intel) | `-x64.dmg` |
| 🐧 Linux | `.AppImage` |

Older versions are available on the [Releases page](../../releases).
See [CHANGELOG.md](CHANGELOG.md) for what's new in each version.

## Requirements

**Android**
- Android 7.0 (Nougat) or newer
- A tablet with a touchscreen

**Windows**
- Windows 10 or newer

**macOS**
- macOS 11 (Big Sur) or newer
- Apple Silicon or Intel Mac

**Linux**
- Any modern 64-bit distribution
- AppImage support (most distros include this out of the box)

## Installation

### Android

1. On the tablet, go to **Settings → Apps → Install unknown apps** and allow your browser or file manager to install APKs.
2. Download the `.apk` file from the link above.
3. Open the downloaded file and tap **Install**.

### Windows

1. Download the `.exe` installer.
2. Run it — Windows SmartScreen may show a warning for unsigned apps; click **More info → Run anyway**.
3. VisuBoard installs and is ready to launch.

### macOS

1. Download the `.dmg` for your chip (Apple Silicon: `-arm64.dmg`, Intel: `-x64.dmg`).
2. Open the `.dmg` and drag VisuBoard into your **Applications** folder.
3. On first launch, right-click the app and choose **Open** to bypass Gatekeeper.

### Linux

1. Download the `.AppImage`.
2. Make it executable: `chmod +x VisuBoard-*.AppImage`
3. Run it: `./VisuBoard-*.AppImage`

## Features

- Support for images and videos in a single presentation
- Adjustable delay between slides, with videos playing through to the end before advancing
- Fit (letterbox) or Fill (crop) display modes
- Customizable logo overlay — size, opacity, edge distance, and position
- Video sound on/off
- Kiosk-ready: runs fullscreen, keeps the screen awake, and auto-starts the presentation on launch

## Getting Started

1. Launch VisuBoard — it opens straight into the presentation screen.
2. Press and hold (Android) or right-click (desktop) anywhere on the screen to open settings.
3. On the **Media** tab, add images and videos from your device. Files are copied into the app, so the presentation keeps working even if the originals are moved or deleted.
4. Reorder media with the arrows on each item, adjust the delay and sound, and choose Fit or Fill.
5. On the **Branding** tab, upload a logo (PNG or SVG) and position it on your slides.
6. Tap or click **Start Presentation** to begin.

## FAQ

**Is my media uploaded anywhere?**
No. VisuBoard works entirely offline — imported files are copied into local storage and never leave the device.

**Will the Android APK trigger a "Play Protect" warning?**
Yes, likely — this is expected for any app installed outside the Play Store. Tap **Install anyway** if you trust the source (this repository).

**Why does Windows / macOS show a security warning?**
VisuBoard is not yet code-signed, so both platforms flag it as an unrecognized app. On Windows, click **More info → Run anyway**. On macOS, right-click the app and choose **Open**.

**How do I update?**
Download the latest release for your platform and install over the existing version. Your media and settings are preserved.

## Support

![Ko-fi Logo](logomarkLogo2024.png)

VisuBoard is free to use. If it helps your business, consider supporting development on ☕️ [Ko-fi](https://ko-fi.com/designsthatwork).

## About

Built with ❤️ by [Designs that Work](https://github.com/designsthatwork).
