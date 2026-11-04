# Fortline — playable builds

**Build the fort. Hold the line.**

This repository contains **playable builds only** (no source code).

## ▶ Play in your browser

**https://graphrlabs.github.io/fortline-play/**

- The web build is **singleplayer only** ("Solo defend"). Hosting/joining a squad needs the desktop builds (browsers can't do the ENet networking).
- First load downloads about 320 MB (cached afterwards). A desktop or laptop with a recent Chrome, Edge or Firefox is recommended.
- The web version uses the Compatibility renderer, so a few effects (SSAO, SSIL, volumetric fog) are turned off compared with desktop.
- Click the page once to enable sound and mouse capture.

## ⬇ Desktop downloads

Grab the latest zip from the [Releases page](../../releases/latest):

| Platform | File |
|---|---|
| macOS (Apple Silicon + Intel) | `Fortline-macos.zip` |
| Windows (x64) | `Fortline-windows.zip` |
| Web (self-host) | `Fortline-web.zip` |

The desktop builds are **not code-signed with a paid certificate**, so your OS will warn you the first time:

- **macOS (Gatekeeper):** the app isn't notarized by Apple, so macOS blocks it the first time (on macOS 15 and later, right-click > Open no longer bypasses this). Either:
  1. Unzip, double-click `Fortline.app`, click **Done** on the warning, then open **System Settings > Privacy & Security**, scroll down and click **Open Anyway** next to Fortline, and confirm. Or
  2. In Terminal, run `xattr -cr /path/to/Fortline.app` (you can drag the app into Terminal to fill in the path), then double-click it.
- **Windows (SmartScreen):** when "Windows protected your PC" appears, click **More info → Run anyway**.

## Build info

See [`BUILD_INFO.txt`](BUILD_INFO.txt) for the exact build that is currently deployed.

*Made by Graphr Labs.*
