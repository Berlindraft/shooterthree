# 🎯 STRIKEZONE — Web FPS

A CS:GO-inspired first-person shooter that runs entirely in the browser using Three.js. No installation, no build step — just drop `index.html` on GitHub Pages and play.

## 🕹️ Controls

| Key | Action |
|-----|--------|
| `WASD` / Arrow Keys | Move |
| Mouse | Look around |
| Left Click (hold) | Shoot |
| `R` | Reload |
| `Shift` | Sprint |
| `Space` | Jump |
| `F` | Toggle flashlight |
| `ESC` | Release mouse |

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload `index.html` to the root
3. Go to **Settings → Pages**
4. Set source to **Deploy from a branch → main → / (root)**
5. Done! Visit `https://yourusername.github.io/your-repo-name`

## ✨ Features

- 🗺️ Full 3D map with cover, pillars, two bomb sites (A & B)
- 👾 Wave-based enemy AI that stalks the player
- 🎯 Headshot detection (4× damage)
- 🔫 Weapon bob, recoil, muzzle flash
- 💉 Slow health regeneration
- 🗺️ Live minimap
- 🔦 Toggleable flashlight
- 📊 Score, kill feed, timer HUD
- ⚠️ Low-ammo warning, reload bar

## Tech

Built with [Three.js r128](https://threejs.org/) loaded from CDN — zero dependencies to install.