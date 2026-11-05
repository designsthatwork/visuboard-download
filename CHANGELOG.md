# Changelog

All notable changes to VisuBoard are documented here.
Format based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [1.2.4] - 2026-11-05

### Fixed
- Quit Application button did nothing on desktop (missing window
  permission)
- Linux AppImage crashed at startup on Fedora/Arch because WebKit
  helper processes were looked up at a Debian-only absolute path

### Changed
- Desktop installers are unsigned; macOS builds now ship as DMG only
  with standardized aarch64/x64 naming

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
