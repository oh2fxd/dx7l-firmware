# Changelog

## [1.2.69] - 2026-04-30
- Built from commit 648691f

## [1.2.68] - 2026-04-30
- Built from commit c97e530

## [1.2.66] - 2026-04-29
- Built from commit b04eee1

## [1.2.65] - 2026-04-28
- Built from commit 7418091

## [1.2.64] - 2026-04-28
- Built from commit fe53403

## [1.2.63] - 2026-04-28
- Built from commit e1327b9

## [1.2.62] - 2026-04-26
- Built from commit 31c3437

## [1.2.60] - 2026-04-26
- Built from commit 5e9e5dd

## [1.2.58] - 2026-04-26
- Built from commit b0c578c

## [1.2.57] - 2026-04-26
- Built from commit c720095

## [1.2.56] - 2026-04-26
- Built from commit d026fef

## [1.2.55] - 2026-04-25
- Built from commit abde313

## [1.2.54] - 2026-04-25
- Built from commit 1b91f19

## [1.2.53] - 2026-04-25
- Built from commit 807748b

## [1.2.52] - 2026-04-25
- Built from commit 42ddd5a

## [1.2.51] - 2026-04-25
- Built from commit e763505

## [1.2.50] - 2026-04-25
- Built from commit f0f6ffe

## [1.2.49] - 2026-04-25
- Built from commit 2bce420

## [1.2.48] - 2026-04-25
- Built from commit 7bba65e

## [1.2.47] - 2026-04-25
- Built from commit 3c5bb15

## [1.2.46] - 2026-04-25
- Built from commit 705fcf8

## [1.2.45] - 2026-04-25
- Built from commit d97e04a

## [1.2.43] - 2026-04-25
- Built from commit 4d3a179

## [1.2.42] - 2026-04-25
- Built from commit 59cf541

## [1.2.41] - 2026-04-25
- Built from commit f728b6d

## [1.2.40] - 2026-04-25
- Built from commit a100105

## [1.2.39] - 2026-04-25
- Built from commit 32e888c

## [1.2.38] - 2026-04-23
- Built from commit 01f5bba

## [1.2.36] - 2026-04-23
- Built from commit 88a906f

## [1.2.33] - 2026-04-20
- Built from commit 73a95eb

## [1.2.32] - 2026-04-19
- Built from commit 51757e8

## [1.2.31] - 2026-04-18
- Built from commit f9441c5

## [1.2.31] - 2026-04-18
- Built from commit f9441c5

## [1.2.30] - 2026-04-18
- Built from commit 4351c6a

## [1.2.29] - 2026-04-18
- Built from commit 5599eeb

## [1.2.28] - 2026-04-17
- Built from commit f79113a

## [1.2.27] - 2026-04-17
- Built from commit 7bbeada

## [1.2.26] - 2026-04-16
- Built from commit 4d967e1

## [1.2.25] - 2026-04-16
- Built from commit fbd98d5

## [1.2.24] - 2026-04-16
- Built from commit 6b02d05

## [1.2.23] - 2026-04-16
- Built from commit 174a17d

## [1.2.22] - 2026-04-16
- Built from commit 97dbd3b

## [1.2.19] - 2026-04-16
- Built from commit a468be1

## [1.2.18] - 2026-04-16
- Built from commit 0c9a101

## [1.2.15] - 2026-04-05
- Built from commit cc82ed6

## [1.2.14] - 2026-04-05
- Built from commit 2ef43ba

## [1.2.13] - 2026-04-05
- Built from commit 10841e2

## [1.2.12] - 2026-02-05
- Built from commit a82292a

## [1.2.11] - 2026-01-08
- Built from commit 4fbf3c7

## [1.2.10] - 2026-01-08
- Built from commit 603219d

## [1.2.9] - 2026-01-08
- Built from commit 0b11c06

## [1.2.8] - 2026-01-08
- Built from commit c2b55c3

## [1.2.7] - 2026-01-08
- Built from commit d02bfd9

## [1.2.6] - 2026-01-08
- Built from commit 7fb8073

## [1.2.5] - 2026-01-07
- Built from commit 67f7dc1

## [1.2.4] - 2026-01-07
- Built from commit 53e4366

## [1.2.3] - 2026-01-06
- Built from commit 94a5b04

## [1.2.2] - 2026-01-05
- Built from commit 72f483b

## v1.1.0 (2026-01-03)
- **New:** WiFi network scanning in web config (scan and select WiFi networks)
- **New:** Reset WiFi & Grid button to clear settings and reboot to AP mode
- **New:** Setup Wizard - guided configuration when starting in AP mode
- **New:** Modes info label on map shows enabled modes (top-left corner)
- AP mode creates "dx7-setup" network (password: hamradio) for initial setup

## v1.0.9 (2026-01-03)
- **New:** Multi-mode selection on LCD (grid layout like band filter)
- **New:** Mode filter added to web configuration interface
- **New:** Map dragging disabled on EU and WORLD views (zoom ≤4)
- Mode button now shows "Modes:X" count format
- MQTT subscriptions updated to handle multiple enabled modes

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
