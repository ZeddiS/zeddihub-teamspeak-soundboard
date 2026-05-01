# Soundboard

[![Latest Release](https://img.shields.io/github/v/release/ZeddiS/zeddihub-teamspeak-soundboard)](https://github.com/ZeddiS/zeddihub-teamspeak-soundboard/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Play sound files into your TeamSpeak 3 microphone stream with hotkeys.

Open the soundboard window from Plugins menu, add slots, browse for .wav files. Each slot has a configurable hotkey (bind in TS3 Settings -> Hotkeys). When triggered, the sound is mixed into your outgoing voice stream so others hear it. Multiple sounds can play simultaneously.

Part of the [**ZeddiHub TeamSpeak Addons**](https://github.com/ZeddiS/zeddihub-teamspeak-addons) collection.

---

## Installation

All download files are in **[Releases](https://github.com/ZeddiS/zeddihub-teamspeak-soundboard/releases/latest)**.

### Option A: TS3 native install (.ts3_plugin) -- recommended

1. Download the .ts3_plugin file matching your TeamSpeak 3 version:

| TS3 client | API | File |
|---|---|---|
| 3.5.0 | 23 | `Soundboard-v1.0.0-TS3-3.5.0-api23.ts3_plugin` |
| 3.5.1 - 3.5.5 | 24 | `Soundboard-v1.0.0-TS3-3.5.1-3.5.5-api24.ts3_plugin` |
| **3.5.6** | **25** | **`Soundboard-v1.0.0-TS3-3.5.6-api25.ts3_plugin`** |
| 3.6.x and newer | 26 | `Soundboard-v1.0.0-TS3-3.6+-api26.ts3_plugin` |

2. Double-click the downloaded file. TS3 client opens an install dialog.
3. Click **Yes** to install. TS3 copies the DLL into the plugins folder.
4. Restart TS3 if requested. Enable the plugin in **Settings -> Plugins**.

### Option B: Manual (.dll)

Download the raw DLL matching your TS3 client version:

- `soundboard_api23_win64.dll` -- TS3 3.5.0
- `soundboard_api24_win64.dll` -- TS3 3.5.1 - 3.5.5
- `soundboard_api25_win64.dll` -- TS3 3.5.6
- `soundboard_api26_win64.dll` -- TS3 3.6.x and newer

Copy the DLL to `%APPDATA%\TS3Client\plugins\`, then in TS3 go to **Settings -> Plugins -> Reload All -> tick Enabled**.

If TS3 reports 'API version not compatible', you have the wrong file -- try a different API number.

## Theme

Plugin dialogs use **TS3 client's native theme**. They look exactly like the rest of the TS3 UI -- no custom Discord-like dark theme. Whatever skin/theme you have set in TS3 will be applied.

## Source code

Source code lives in the [collection repo](https://github.com/ZeddiS/zeddihub-teamspeak-addons), folder `Soundboard/`. CMake build instructions are there.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## License

MIT -- see [LICENSE](LICENSE).

---

## Links

- **ZeddiHub web**: https://zeddihub.eu
- **ZeddiHub Tools**: https://zeddihub.eu/tools/
- **Author**: https://zeddis.xyz
- **Collection**: [zeddihub-teamspeak-addons](https://github.com/ZeddiS/zeddihub-teamspeak-addons)

**Sister plugins:** [Poke Bot](https://github.com/ZeddiS/zeddihub-teamspeak-pokebot) | [Follow](https://github.com/ZeddiS/zeddihub-teamspeak-follow) | [MoveSpam](https://github.com/ZeddiS/zeddihub-teamspeak-movespam) | [Soundboard](https://github.com/ZeddiS/zeddihub-teamspeak-soundboard)

---

(C) 2026 [ZeddiHub.eu](https://zeddihub.eu) -- zeddis.xyz
