# DX7L Firmware Changelog

## v1.0.8 (2026-01-03)
- **New:** Dark Mode Map toggle in LCD Display Settings
- **New:** OH activity now shows elapsed time (e.g., "OH: OH2XYZ -> W1ABC (20m) 3m")
- OH activity label auto-hides after 15 minutes (spot window)

## v1.0.7 (2026-01-03)
- **New:** Release notes displayed on OTA update page
- Shows what's new before installing updates

## v1.0.6 (2026-01-03)
- **Fixed:** Spot flash bug - spots no longer flash when old ones expire
- Efficient `expire_old_spots()` function removes only expired spots
- Full redraw now only occurs every 30 minutes (was every second)
- Smoother visual experience during normal operation

## v1.0.5 (2026-01-03)
- **New:** 🌙 Dark Mode Map - Toggle to invert map colors for night viewing
- Dark mode preference saved to SD card
- Web config checkbox to enable/disable dark mode

## v1.0.4 (2026-01-02)
- OTA update test release
- No functional changes from v1.0.3

## v1.0.3 (2026-01-02)
- **New:** Boot splash screen with "DX7L" title and version
- **New:** Boot progress bar showing initialization status
- Visual feedback during startup

## v1.0.2 (2026-01-02)
- Fixed OTA version checking (now uses firmware.json)
- OTA downloads firmware URL from manifest

## v1.0.1 (2026-01-02)
- **New:** OTA (Over-The-Air) firmware updates via web interface
- Check for updates from GitHub repository
- Download and apply firmware updates wirelessly
- OTA tab added to web configuration

## v1.0.0 (2026-01-02)
- Initial release with OTA support
- MAX_VISIBLE_SPOTS=150 limit for stability
- DX spot mapping from PSKReporter MQTT feed
- Configurable bands, modes, and filters
- Friends list with priority alerts
- Web-based configuration interface
