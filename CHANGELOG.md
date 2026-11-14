# Changelog

All notable changes to VisuBoard are documented here.
Format based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

This is the unified changelog for both apps - mobile (Android) and
desktop (macOS / Windows / Linux). Changes that apply to both are listed
under shared `Added` / `Changed` / `Fixed` sections; platform-specific
changes are grouped under `### Mobile` and `### Desktop`.


## [1.3.0] - 2026-11-14

### Mobile

#### Added
- Android TV support: the app now appears on the TV home screen with a
  dedicated banner tile, and installs on non-touchscreen devices
- Remote-friendly controls: hold the OK button on the remote to open
  settings (same gesture as touch press-and-hold), D-pad arrows move
  between controls in the settings sheet, and Back closes it
- TV usage notes in the Help tab, including a codec caveat (MP4/H.264
  plays reliably; HEVC/MKV may not decode on every TV box)

### Desktop

- Version Bump

## [1.2.4] - 2026-11-05

### Mobile

#### Changed
- Release asset renamed to `VisuBoard-<version>_aarch64.apk`
- Release notes now generated from this changelog

No app-facing changes since 1.2.3 - this is a distribution tooling update.

### Desktop

#### Fixed
- Quit Application button did nothing on desktop (missing window
  permission)
- Linux AppImage crashed at startup on Fedora/Arch because WebKit
  helper processes were looked up at a Debian-only absolute path

#### Changed
- Desktop installers are unsigned; macOS builds now ship as DMG only
  with standardized aarch64/x64 naming

## [1.2.3] - 2026-10-31

Applies to: Mobile + Desktop

### Added
- Reset button on all settings tabs, with a confirmation that clears the
  media library and restores default settings
- Ko-fi support link on the About tab
- Move-to-start and move-to-end buttons on each media item

### Changed
- Slideshow now pauses while settings is open and restarts from the first
  item when the sheet closes
- Restored the X button to close settings
- Settings controls use inline label + switch layout

### Fixed
- Media fit label overlapping the segmented control

## [1.2.1] - 2026-10-30

Applies to: Mobile + Desktop

### Added
- Initial tablet release: fullscreen slideshow of imported images and
  videos with configurable delay, sound toggle and Fit/Fill display modes
- Media library: add from gallery or files, reorder, remove, clear all
- Branding: PNG/SVG logo overlay with size, opacity, edge distance and
  corner/center position
- Long-press gesture opens settings (Media, Branding, Help, About tabs)
- Kiosk behavior: immersive fullscreen, screen stays awake, auto-start
