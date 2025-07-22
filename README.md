#  Alight-Motion-PC (Open Source)

>  An open-source desktop motion graphics & video editing tool inspired by Alight Motion — made for AMV editors, mobile creators, and low-spec warriors.

---

##  Why?

- Alight Motion is Android-only and closed-source. 
- After Effects is heavy AF and paywalled. 
- Creators like us need a **lightweight, offline, free** desktop tool with AM-style FX. 🔥

So we said: *“fuck it, let’s build our own.”*

---

##  Features (Planned)

-  Keyframe timeline (position, scale, rotation, blur)
-  Layer system (video, audio, text, vectors)
-  Effects: Motion blur, Edge Glow, Z-depth transitions
-  Real-time preview (GPU accelerated)
-  Export to MP4 (via ffmpeg or render queue)
-  Import from Alight Motion `.xml` (future goal)

---
##  Quick Start (No Setup Needed)

1. Press `.` on your keyboard when viewing this repo on GitHub — it opens the full code editor in your browser (via GitHub.dev).
2. Or clone locally:
   ```bash
   git clone https://github.com/GaneshVB003/Alight-Motion-Pc.git
   cd Alight-Motion-Pc
   npm install
   npm run dev

## 🛠 Tech Stack

| Layer | Tech |
|-------|------|
| UI | Electron + React (or Svelte/QT - TBD) |
| Animation Engine | Custom or Lottie |
| Video Processing | ffmpeg |
| Graphics | WebGL / OpenGL / Skia |
| Audio Sync | Wavesurfer.js |

---

##  How to Run (Dev Mode)

```bash
git clone https://github.com/ganeshvb003/Alight-Motion-PC
cd Alight-Motion-PC
npm install
npm start
