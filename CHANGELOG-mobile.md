# Changelog

All notable changes to VisuBoard are documented here.
Format based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [1.2.4] - 2026-11-05

### Changed
- Release asset renamed to `VisuBoard-<version>_aarch64.apk`
- Release notes now generated from this changelog; mobile changelog is
  published as `CHANGELOG-mobile.md` on the download repo

No app-facing changes since 1.2.3 - this is a distribution tooling update.

## [1.2.3] - 2026-10-31

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

### Added
- Initial tablet release: fullscreen slideshow of imported images and
  videos with configurable delay, sound toggle and Fit/Fill display modes
- Media library: add from gallery or files, reorder, remove, clear all
- Branding: PNG/SVG logo overlay with size, opacity, edge distance and
  corner/center position
- Long-press gesture opens settings (Media, Branding, Help, About tabs)
- Kiosk behavior: immersive fullscreen, screen stays awake, auto-start
