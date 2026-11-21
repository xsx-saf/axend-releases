# Axend — downloads

Get the newest version from **[Releases](../../releases/latest)** and pick your system:

| System | Download | How |
|---|---|---|
| **Windows** 10/11 | `Axend.exe` | Run it. It installs itself to `%LOCALAPPDATA%\Axend` and adds itself to the Start menu. |
| **Mac** (Apple chip) | `Axend-macos-aarch64.dmg` | Open it and drag Axend to Applications. |
| **Linux** (Debian, Ubuntu) | `Axend-linux-x86_64.deb` | Open it with your software installer, or `sudo apt install ./Axend-linux-x86_64.deb`. |
| **Linux** (any) | `Axend-linux-x86_64.AppImage` | Make it executable (`chmod +x`) and run it. |

iPhone and Android versions are coming.

Axend keeps everything on your device. It goes online only to check for a newer version here (and, later, to activate a licence) — never with your data. Once installed, it checks this page by itself and offers each update; every download is checked against its SHA-256 before it runs (the `.sha256` files are there to check by hand, too).

**It isn't code-signed yet**, so your system may warn that it's from an unknown developer:

- **Windows:** choose **More info → Run anyway**.
- **Mac:** the first time, right-click Axend in Applications and choose **Open**, then **Open** again (or System Settings → Privacy & Security → **Open Anyway**).

This repository holds downloads only. The source code is private.
