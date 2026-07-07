# Buoy Desktop

[![Latest release](https://img.shields.io/github/v/release/Buoy-gg/Buoy-Desktop?color=brightgreen&label=release)](https://github.com/Buoy-gg/Buoy-Desktop/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Buoy-gg/Buoy-Desktop/total?color=blue)](https://github.com/Buoy-gg/Buoy-Desktop/releases)
[![Platforms](https://img.shields.io/badge/platform-macOS%20·%20Windows%20·%20Linux-9cf)](https://github.com/Buoy-gg/Buoy-Desktop/releases/latest)

**Every Buoy tool, full screen.**

Buoy Desktop mirrors the [BUOY Devtools](https://github.com/Buoy-gg/buoy) running inside your React Native app to a native desktop dashboard — every request, state change, render, and frame, streamed live from any connected device. It's the same session as the floating menu on the phone and the [MCP server](https://buoy.gg/buoy/latest/docs/mcp) in your editor: one live app, three ways in.

📚 **[Full Documentation](https://buoy.gg/buoy/latest/docs/desktop)** · 🚀 **[Get Buoy for your app](https://github.com/Buoy-gg/buoy)**

<!-- TODO(austin): hero image — replace this comment with a desktop screenshot/GIF, e.g.
![Buoy Desktop](https://github.com/user-attachments/assets/YOUR-ASSET-ID)
-->

---

## What it does

- **Full-screen tools** — Network, Storage, Console, Events, Redux, Zustand, Jotai, Routes, React Query, Env, Impersonate, and Bench, each in a real desktop panel
- **Live performance HUD** — UI/JS FPS, CPU, and memory streamed from the connected device
- **Remote actions** — edit storage values, refetch and invalidate queries, dispatch actions, simulate loading/error states, and navigate the app, from your desk
- **Screenshot tool** — capture the iOS Simulator: drag a region, or type a `testID` and get a tight auto-crop of that component (LLM-friendly)
- **Multi-device** — switch between connected simulators and physical devices (iOS, Android, web) mid-session
- **Make it yours** — Default, Biomech, and Light themes with animated glow effects
- **Auto-updates** — install once; new releases apply themselves

---

## Download & Install

Buoy Desktop is a **[Buoy Pro](https://buoy.gg/pricing)** feature — and every weekend, Pro unlocks free for everyone.

1. Get a license at **[buoy.gg/pricing](https://buoy.gg/pricing)** (14-day trial, no credit card)
2. Download the app for your platform from **[Releases](https://github.com/Buoy-gg/Buoy-Desktop/releases/latest)**
3. Launch it, then open your app with Buoy devtools running — devices connect automatically

---

## Connect Your App

Your app needs [BUOY Devtools](https://github.com/Buoy-gg/buoy) installed — see the [Quick Start](https://buoy.gg/buoy/latest/docs/quick-start). Buoy Desktop runs a local broker on port `42831`:

| Where your app runs   | Broker URL                    |
| --------------------- | ----------------------------- |
| iOS Simulator / web   | `http://localhost:42831`      |
| Android emulator      | `http://10.0.2.2:42831`       |
| Physical device       | `http://<your-computer-ip>:42831` |

---

## Nothing Leaves Your Machine

Buoy's tools run inside your app's process and sync to Buoy Desktop over the local broker — localhost only, no cloud, no remote connections.

---

## License

Proprietary software. © Buoy LLC. All rights reserved.

See [Terms of Service](https://buoy.gg/terms) for usage terms.

---

> Looking for the legacy open-source React Query desktop tool that used to live here? It has been superseded by Buoy Desktop, which supports the full Buoy toolset.
