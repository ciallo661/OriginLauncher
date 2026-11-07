# Origin Launcher

**A modern, lightweight Minecraft: Java Edition launcher built with Python & Tkinter.**

[![English](https://img.shields.io/badge/README-English-blue.svg)](README.md)
[![中文](https://img.shields.io/badge/README-中文-red.svg)](README_zh.md)

---

## ✨ Features

- 🎮 **Offline account** — create a profile with just a nickname, no login required
- 🪪 **Microsoft (premium) login** — OAuth device-code flow, no password handling
- 🌐 **External / Yggdrasil login** — connect to third-party auth servers
- 📦 **One-click version install** — download and manage Minecraft versions
- 🎨 **Native dark UI** — Tkinter-based, DPI-aware, no heavy dependencies
- ⚡ **Fast startup** — packaged as a single `.exe` with PyInstaller

## 📥 Download

Grab the latest installer from the [Releases page](https://github.com/your-repo/OriginLauncher/releases).

| File | Description |
|---|---|
| `OriginLauncher-Setup-vX.Y.Z.exe` | Windows installer (recommended) |
| `OriginLauncher.exe` | Portable single-file binary |

> Requires Windows 10 or later. No Java pre-install needed (runtime is downloaded with the version).

## 🖼️ Screenshots

*To be added.*

## 🛠️ Built With

- **Python 3.13** + **Tkinter** — GUI
- **PyInstaller** — packaging
- **Pillow** — icon rendering
- **Inno Setup 7** — installer script

## 📁 Project Structure

```
mc-launcher/
├── mc_launcher.py          # Main application
├── OriginLauncher.spec      # PyInstaller spec
├── version_info.txt         # Windows version info
├── installer.iss             # Inno Setup script
└── *.png                    # UI icons & assets
```

## 📜 License

This project is for personal and educational use. Not affiliated with Mojang or Microsoft.

---

<p align="center">Built with ❤️ for the Minecraft modding community</p>
