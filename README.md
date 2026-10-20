# MYGStat

<p align="center">
  <strong>The Ultra-Lightweight, Zero-UAC Windows System Tray Companion</strong><br>
  Built for gamers, developers, and power users who demand speed without bloat.
</p>

<p align="center">
  <a href="https://github.com/asone26/mygstat/releases/latest"><img src="https://img.shields.io/github/v/release/asone26/mygstat?label=Download" alt="Latest release"></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(x64)-0078D6.svg" alt="Platform">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-FSL--1.1--MIT-blue.svg" alt="License: FSL-1.1-MIT"></a>
</p>

---

## ⚡ Why MYGStat?

Standard task managers and system tools are heavy, trigger intrusive UAC prompts, and can conflict with game anti-cheats (e.g., Riot Vanguard, Easy Anti-Cheat).

**MYGStat** sits quietly in your system tray using minimal resources (~20 MB RAM) and gives you instant access to critical system controls without administrator prompts.

- 🛡️ **Anti-Cheat Safe & Zero UAC** — no kernel drivers, no admin elevation popups during daily use.
- ⚡ **0.5-Second Click-to-Kill** — terminate resource-hogging processes instantly, with human-readable memory (3.5 GB, 718 MB).
- 🧹 **Uninstall Watcher & Leftover Cleaner** — tracks app uninstalls and sweeps leftover `AppData` residue and orphaned caches.
- 🔓 **File Unlocker** — find and release file locks held by stubborn processes in one click.
- 🎧 **Instant Audio & Window Controls** — hotkeys to switch audio output (Headset ⇄ Speaker) and pin windows Always-on-Top.
- 🎨 **Windows 11 Native Fluent UI** — readable dark flyout with slim scrollbars and clean typography.
- 🌐 **7 Languages** — Korean, English, Spanish, Simplified Chinese, Japanese, French, German (follows your system language).

---

## 🚀 Features

| Feature | Description |
| :--- | :--- |
| **System Resource Monitor** | Real-time 1-second CPU, GPU (engine/3D) and RAM usage with mini gauges. |
| **Vector Mini Sparklines** | 60-second to 5-minute rolling trend curves for CPU, GPU and RAM. |
| **Extended Stats** | Network speed (▲/▼), disk free/total capacity, laptop battery level and charging time. |
| **Bluetooth Peripheral Battery** | Battery levels of wireless mice, keyboards and headsets. |
| **Temperature Sensors** | ACPI/WMI thermal zone monitoring — no kernel drivers, no UAC. |
| **Instant Process Killer** | Top CPU/RAM processes at a glance; end unresponsive apps instantly. |
| **AppData Leftover Sweeper** | Finds leftover folders in `AppData\Local`, `Roaming` and `ProgramData` after uninstalls. |
| **Safe Junk Cleaner** | Manual scan of aged (>7 days) `%TEMP%` files, crash dumps and error reports — moved to the Recycle Bin. |
| **File Unlocker** | "File is in use by another program"? See which process holds it, then unlock or delete. |
| **Quick Audio Switcher** | Switch default playback devices with a global hotkey. |
| **Always-on-Top Pinning** | Pin the foreground window on top with a shortcut. |
| **Screen OCR** | Capture an area of the screen and copy its text to the clipboard. |

---

## 📦 Download & Install

Get the latest version from the **[Releases](https://github.com/asone26/mygstat/releases/latest)** page.

| File | Description |
| :--- | :--- |
| `MYGStat-Setup-<version>-x64.exe` | **Recommended.** Per-user installer with optional auto-start on Windows startup. |
| `MYGStat-Portable-<version>-x64.zip` | Portable folder — extract anywhere and run `MYGStat.UI.exe`. |
| `MYGStat-Portable-<version>-x64.exe` | Portable single executable — no installation needed. |

### Installer
1. Download and run `MYGStat-Setup-<version>-x64.exe` (no administrator rights required).
2. Optionally check **"Start MYGStat automatically on Windows startup"**.

### Portable
1. Download the `.zip` and extract it (e.g., `C:\Tools\MYGStat`), then run `MYGStat.UI.exe`.
2. Or just run the single portable `.exe` directly.

> **Windows SmartScreen notice**
> The binaries are not code-signed yet, so Windows may show *"Windows protected your PC"*.
> Click **More info → Run anyway** to continue. You can verify file integrity with the SHA-256 checksums listed in each release.

### Requirements
- Windows 10 (build 19041+) or Windows 11, x64
- No .NET installation needed (self-contained)

---

## ⌨️ Default Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>A</kbd> | Toggle default audio playback device |
| <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd> | Toggle "Always on Top" for the active window |
| <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>M</kbd> | Open the MYGStat flyout |

*(All shortcuts can be remapped or disabled in Settings.)*

---

## 🐞 Feedback

Found a bug or have a feature request? Please open an [issue](https://github.com/asone26/mygstat/issues).

---

## 📄 License

Distributed under the **Functional Source License, Version 1.1, MIT Future License (FSL-1.1-MIT)**. See [LICENSE](LICENSE) for details.
