# NiXX-Studio™

**The official integrated development environment for NiXX-32™ ROM development.**

NiXX-Studio™ is a professional IDE designed specifically for creating ROMs for the various NiXX™ platform. It provides a complete suite of tools for asset creation, code editing, visual scripting, and ROM building.

> **Pre-Release Notice:** This is an early pre-release version. Features may be incomplete or subject to change.

---

## Features

### Editors
- **Code Editor** - Syntax highlighting for Lua and C++, NiXX™ API autocomplete, bracket matching, find/replace
- **Sprite Editor** - 256-color indexed palette editor with drawing tools, animation timeline
- **Tilemap Editor** - Multi-layer tilemap creation with parallax support (3-4 layers)
- **Node Editor** - Visual scripting with 60+ nodes for game logic, graphics, audio, and input
- **Scene Editor** - Entity-component based scene composition
- **NiXX-Tracker™** - Chiptune music creation with FM synthesis and PCM samples

### Core Features
- **Project Management** - Create, open, and manage NiXX™ projects
- **Asset Pipeline** - Import and convert sprites, tilemaps, audio, and fonts
- **Build System** - Compile and package projects into NiXX™ ROM format
- **Emulator Integration** - Run and test ROMs directly from the IDE
- **Dark Theme** - Professional dark UI designed for extended development sessions

### Supported Platforms
- Windows 10/11 (64-bit)

---

## Installation

1. Download the latest release from the [Releases](https://github.com/NiXX-Team/NiXX-Studio/releases) page
2. Extract the archive to your preferred location
3. Run `nixx-studio.exe`

### System Requirements
- **OS:** Windows 10 or later (64-bit)
- **RAM:** 4 GB minimum, 8 GB recommended
- **Disk:** 500 MB free space
- **Display:** 1280x720 minimum resolution

---

## Quick Start

1. **Create a New Project**
   - File → New Project
   - Choose a project name and location
   - Select the target hardware variant (NiXX-32™ or the enhanced NiXX-32+™)

2. **Add Assets**
   - Right-click in the Outliner panel to add assets
   - Import sprites, tilemaps, and audio files

3. **Write Code**
   - Create `.lua` or `.nixx` script files
   - Use the built-in autocomplete for NiXX™ API functions

4. **Build & Run**
   - Build → Build ROM (Ctrl+B)
   - Build → Run (F5)

---

## Documentation

Full documentation coming soon.

For now, refer to the in-editor tooltips and autocomplete suggestions for API reference.

---

## Feedback & Support

This is a pre-release version. If you encounter issues or have suggestions:

- Open an issue on this repository
- Include steps to reproduce any bugs
- Specify your Windows version and hardware

---

## License

NiXX-Studio™ is proprietary software. See [LICENSE.MD](LICENSE.MD) for the full End User License Agreement.

**© 2025 Starsick™. All Rights Reserved.**

---

## Acknowledgments

Built with:
- Qt 6
- SDL2
- YMFM (FM synthesis)
- Lua 5.4
