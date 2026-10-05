# Theater

Plugins for OBS Studio on Windows. They turn stream events into effects on your avatar, read your chats and alerts, and run your stream's triggers and commands.

| Plugin | What it does |
|---|---|
| **Theater Scene** | Redeems that hit your avatar's real outline (throwables, water, fire, lightning, reactions, Lua redeems), poses, the Scene Studio, Rhai chat and alerts, and docks. |
| **Theater Reader** | Reads Twitch, Kick and YouTube chat and alerts inside OBS, for Theater Scene and the Control Panel. |
| **Theater Control Panel** | Triggers, commands and modules in an OBS dock, and the Theater Web Source, which replaces Browser Source. |

## Install

1. Download **Theater-Installer.exe** from the newest **Theater Installer** release on the [Releases](https://github.com/Mortygotvr/Theater-Releases/releases) page.
2. Close OBS and run the installer. It isn't signed, so Windows may say it protected your PC: click **More info**, then **Run anyway**.
3. Click **Install** for each plugin you want, then start OBS. Everything is in the **🎭 Theater** menu.

Run the installer again any time to update. Your settings are never touched.

**By hand:** download a plugin's zip from its release, then extract it into `C:\ProgramData\obs-studio\plugins` while OBS is closed.

## Requirements

- Windows 10 or 11, 64-bit
- OBS Studio 30 or newer
- For the Control Panel, Microsoft Edge WebView2 Runtime. Windows 11 includes it, and most Windows 10 PCs have it.

## Releases

Each plugin's versions are released here, tagged `<plugin>-v<version>`: `theater-scene-v…`, `theater-reader-v…`, `theater-control-panel-v…` and `theater-installer-v…`. They're pre-releases while Theater is at 0.x.

## License

GPL-2.0-or-later. See [LICENSE](LICENSE).
