---
name: wallpaper-claw-skill
description: Generate stunning AI wallpapers for mobile, desktop, ultrawide, and iPad — sized perfectly for each device in one command.
version: 1.0.0
metadata:
  openclaw:
    requires:
      env:
        - NETA_TOKEN
      bins:
        - node
    primaryEnv: NETA_TOKEN
    emoji: "🖼️"
    homepage: https://github.com/BarbaraLedbettergq/wallpaper-claw-skill
---

# Wallpaper Claw Skill

Generate AI wallpapers sized perfectly for any device.

## Commands

```bash
node wallpaper.js gen <prompt> [--device mobile|desktop|ultrawide|ipad] [--char name] [--style name]
```

## Device Presets

| Device | Size | Ratio |
|--------|------|-------|
| `mobile` | 576×1024 | 9:16 |
| `desktop` | 1024×576 | 16:9 |
| `ultrawide` | 1024×432 | 21:9 |
| `ipad` | 768×1024 | 3:4 |

## Setup

```
NETA_TOKEN=your_token_here
```
in `~/.openclaw/workspace/.env`
