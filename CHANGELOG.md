# Changelog

All notable changes to **Soundboard** are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [1.0.0] - 2026-05-01
### Added
- Initial release
- Plugins menu -> Open Soundboard opens slot grid
- Add unlimited slots (up to 32 -- one per pre-registered hotkey)
- Browse and assign .wav files to slots, set per-slot volume
- 32 hotkeys pre-registered (soundboard_play_1 .. soundboard_play_32)
- Bind hotkeys in TS3 Settings -> Hotkeys -> Plugins -> ZeddiHub Soundboard
- Audio mixed into mic stream via ts3plugin_onEditCapturedVoiceDataEvent
- WAV decoder (16-bit PCM mono/stereo, any sample rate via linear resample)
- Slot config persisted to %APPDATA%/TS3Client/plugins/soundboard.json
