# UA Changer Chrome — v5.0.0

> 451 presets · 118 unique devices · Chrome 145–148 · Android 13–16 · 9 manufacturers

---

## What's New

### Full Chrome Version Matrix
Every device now ships with **Chrome 145, 146, 147, and 148** variants. Previous releases had only 1–2 Chrome versions per device — that gap is now closed across all 118 devices and all 9 manufacturers.

### Android 16 Presets
Android 16 presets added for:
- Samsung Galaxy S25 Ultra / S25+ / S25 / S25 Edge
- Samsung Galaxy Z Fold7 / Z Flip7
- Samsung Galaxy A56 / A36
- Google Pixel 9 Pro XL / Pixel 9 Pro / Pixel 9 / Pixel 9a / Pixel 9 Pro Fold

### Samsung — 205 Presets, 51 Devices
New additions this release:

| Series | New Devices |
|--------|------------|
| Galaxy M | M55 5G, M35 5G, M15 5G |
| Galaxy A | A26 5G, A06 5G, A05s |
| Galaxy S24 | S24 FE |
| Galaxy Z | Z Flip6 |
| Galaxy Tab S9 | Ultra, +, FE, standard |
| Galaxy Tab A | A9+, A9 |

### 4 Independent Filter Rows
- **Type** — Android / iOS / Tablet / Bot
- **Manufacturer** — Samsung / Pixel / Xiaomi / OnePlus / OPPO / vivo / Huawei / Apple
- **Android Version** — A16 / A15 / A14 / A13
- **Chrome Version** — 148 / 147 / 146 / 145

Android version pills are color-coded per preset row: A16 cyan · A15 blue · A14 purple · A13 grey.

---

## Preset Count by Manufacturer

| Manufacturer | Presets | Unique Devices |
|---|---|---|
| 🔵 Samsung | 205 | 51 |
| 🔷 Google Pixel | 64 | 10 |
| 🟠 Xiaomi | 60 | 15 |
| 🍎 Apple | 32 | 10 |
| 🟢 OPPO | 24 | 6 |
| 💜 vivo | 24 | 6 |
| 🔴 OnePlus | 20 | 5 |
| 🟡 Huawei | 20 | 5 |
| 🤖 Bot | 2 | 2 |
| **Total** | **451** | **118** |

---

## Bug Fixes

- Fixed Kotlin compile error — unescaped quote character inside device name string crashed the build
- Fixed string interpolation compile error — `$V148` template variables replaced with literal version strings throughout
- Removed `WINDOWS` and `MACOS` categories — Android-only focus, cleaner enum
- All 451 UA strings validated — balanced quotes, no stray characters, balanced parentheses

---

## Requirements

- Android 8.0+ (SDK 26+)
- Magisk 24+
- Root access
- Chrome
---

## Installation

**1 — Magisk Module**
```bash
cd magisk-module
zip -r ../UAChangerChrome-module.zip .
# Magisk Manager → Modules → Install from ZIP
```

**2 — Companion App**

Download the APK from the [Releases](../../releases) page and install manually.

---

*Telegram: [@enployer](https://t.me/enployer)*

