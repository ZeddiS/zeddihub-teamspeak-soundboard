# Changelog

All notable changes to **SoundBoard** are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [1.1.0] - 2026-05-01
### Changed
- Plugin renamed: 'ZeddiHub Soundboard' -> 'SoundBoard'
- Dialog UI redesigned as colored tile grid (click to play, right-click for options)
- Each tile now has a CUSTOMIZABLE COLOR (right-click -> Change color, opens QColorDialog)
- Diagnostic log entries added (TS3 Tools -> Client log shows when sounds are queued + when audio callback fires)
### Fixed
- WAV decoder now supports 24-bit PCM, 32-bit PCM, 32-bit float (was only 16/8-bit)
- Mix function fixed for stereo capture (was advancing position 2x too fast on stereo mics)

## [1.0.0] - 2026-05-01
### Added
- Initial release
- Plugins menu -> Open Soundboard opens slot grid
- Add unlimited slots (up to 32 -- one per pre-registered hotkey)
- Browse and assign .wav files to slots, set per-slot volume
- 32 hotkeys pre-registered (soundboard_play_1 .. soundboard_play_32)
- Audio mixed into mic stream via ts3plugin_onEditCapturedVoiceDataEvent
