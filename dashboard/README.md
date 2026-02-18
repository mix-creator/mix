# OpenClaw 3D Avatar Dashboard

A beautiful, interactive 3D dashboard for your OpenClaw assistant with animated avatar support.

## 🚀 Quick Start

### 1. Get Your 3D Model from Meshy

1. Go to your Meshy model: https://www.meshy.ai/3d-models/Goblin-v2-019b811d-de66-7276-a14e-e9b1d969f151
2. Click **Download** 
3. Select **GLB** format (Binary glTF)
4. Save it to this folder as `goblin.glb`

### 2. Open the Dashboard

Double-click `index.html` or open it in your browser:
```bash
open /Users/mix/.openclaw/workspace/dashboard/index.html
```

## ✨ Features

- **🎭 3D Avatar Display** — Load and animate your GLB/GLTF models
- **🎮 Interactive Controls** — Orbit, zoom, pan around your avatar
- **⏯️ Animation Control** — Play/pause animations
- **🔲 Wireframe Mode** — Toggle wireframe view
- **📊 System Status** — Live OpenClaw status indicators
- **📁 Drag & Drop** — Drop any GLB file to load it instantly

## 🎨 Controls

| Button | Action |
|--------|--------|
| ⏯️ Play/Pause | Toggle animation playback |
| 🎥 Reset View | Return to default camera position |
| 🔲 Wireframe | Toggle wireframe rendering |
| 📂 Load Model | Browse for a GLB/GLTF file |

**Mouse Controls:**
- **Left Click + Drag** — Rotate around model
- **Right Click + Drag** — Pan camera
- **Scroll** — Zoom in/out

## 📁 File Structure

```
dashboard/
├── index.html          # Main dashboard
├── goblin.glb          # Your 3D avatar (you add this)
└── README.md           # This file
```

## 🛠️ Customization

### Change the Avatar

Simply replace `goblin.glb` with any other GLB file, or use the **Load Model** button to browse for a different model.

### Supported Formats

- ✅ GLB (recommended)
- ✅ GLTF
- ⚠️ OBJ, FBX (need conversion)

### Getting More Models

- **Meshy.ai** — AI-generated 3D models
- **Sketchfab** — Free/paid 3D models
- **ReadyPlayer.me** — Avatar generators
- **Mixamo** — Animated characters

## 🔧 Troubleshooting

**Model not showing?**
- Make sure the file is named `goblin.glb` (case-sensitive)
- Check browser console (F12 → Console) for errors
- Ensure the file is a valid GLB format

**Animations not playing?**
- Not all GLB files contain animations
- Use the **Load Model** button to try different files

**Slow performance?**
- Try a lower-poly model
- Close other browser tabs
- Check wireframe mode to see polygon count

## 📝 Notes

- Dashboard uses **Three.js** loaded from CDN (no local install needed)
- Works offline after first load (cached)
- Your model data never leaves your computer

## 🎯 Future Ideas

- [ ] Voice-activated animations (avatar reacts when you speak)
- [ ] Integration with OpenClaw status API
- [ ] Multiple avatar slots
- [ ] Background themes
- [ ] Particle effects

---

Enjoy your new dashboard! 🐾
