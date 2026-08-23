# Plathott - Desktop Edition

My first GB Studio game, now available as a desktop application for Windows and Linux!

A fast-paced platformer featuring a speedy chipmunk character.

## Features

- 🎮 Full platformer gameplay
- 🐿️ Chipmunk protagonist sprites
- 🖥️ Native Windows & Linux support
- ⚡ Smooth performance

## Credits

- **Art & Box Art**: Created by myself
- **Sprites**: [Think Epic's GB Studio Sprites](https://thinkepic.itch.io/gb-studio-sprites)
- **Music**: Coming soon!

## Installation

### Windows
1. Download the latest `.exe` installer from [Releases](../../releases)
2. Run the installer
3. Launch from Start Menu or Desktop shortcut

### Linux
1. Download the `.AppImage` or `.deb` from [Releases](../../releases)
2. **For AppImage**: Make it executable and run
   ```bash
   chmod +x Plathott-*.AppImage
   ./Plathott-*.AppImage
   ```
3. **For .deb**: Install via package manager
   ```bash
   sudo dpkg -i plathott-*.deb
   ```

## Development

### Setup

```bash
npm install
```

### Run in Development Mode

```bash
npm start
```

### Build Installers

```bash
# Build for Windows
npm run build:win

# Build for Linux
npm run build:linux

# Build for both
npm run build
```

## Links

- [Play Online on itch.io](https://healthyburger.itch.io/plathott)
- [GitHub Repository](https://github.com/itsjustsomecoolcode19393/plathott)

---

**Version 1.0.0** - Desktop Edition