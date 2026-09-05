# MacOS Desktop

A standalone Electron desktop simulator inspired by the macOS desktop experience.

> **Important:** this does not contain or boot Apple's macOS operating system. It is an independent desktop environment that recreates familiar desktop concepts and runs on Windows, Linux, and macOS.

## Included

- macOS-style menu bar and live clock
- Dock with hover animations
- Finder-style file browser
- System Settings window
- Terminal with basic commands
- Notes with local persistence
- Calculator
- Launchpad
- Desktop icons and context menu
- Draggable windows
- Cross-platform Electron packaging

## Run

```bash
npm install
npm start
```

## Build

```bash
npm run dist
```

GitHub Actions also builds installers for Windows, Linux, and macOS when a `v*` tag is pushed.
