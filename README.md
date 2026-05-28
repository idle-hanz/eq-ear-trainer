# EQ Ear Trainer

**Master your ears for professional mixing and music production.**

An interactive, browser-based ear training tool focused on audio equalization (EQ). Use real-time Web Audio API to practice identifying frequency bands and matching EQ curves by ear.

## 🎯 Features

- **Frequency Identification Game**: A random EQ band is boosted — listen and guess which frequency range it is!
- **EQ Matching Challenge**: Adjust 7 band sliders to match a hidden target EQ by ear alone. Get instant accuracy scoring.
- **Realistic Audio Engine**: Uses peaking filters on generated noise for authentic EQ response (great with headphones).
- **Progress Tracking**: Streaks, accuracy %, session stats. Local storage saves your best scores.
- **Fully Responsive**: Beautiful dark UI works perfectly on desktop, tablet, and mobile.
- **Zero Dependencies**: Pure HTML + Tailwind + Vanilla JS. Runs instantly in any modern browser.

## 🚀 Quick Start

1. Visit the live site (after GitHub Pages is enabled): https://idle-hanz.github.io/eq-ear-trainer/
2. Put on headphones for best results.
3. Choose a training mode and start improving your frequency recognition!

## 🎧 How It Works

The app generates broadband noise and applies precise peaking EQ filters (common in mixing consoles and DAWs). Training with noise helps isolate frequency perception without musical bias.

**Pro Tip**: Train 10–15 minutes daily. You'll notice huge improvements in your mixing decisions within a week!

## 🔧 Tech Stack

- HTML5 Web Audio API (BiquadFilterNode peaking)
- Tailwind CSS (via CDN)
- Vanilla JavaScript

## 🚢 Deployment

This repository is set up for GitHub Pages. To activate:

1. Go to your repo **Settings** → **Pages**
2. Under "Build and deployment" → **Source** → Select **Deploy from a branch**
3. Branch: `main` | Folder: `/ (root)`
4. Save — your site will be live in ~1 minute at the URL above.

## 👏 Credits & Next Steps

Built for you by **Grok** (xAI) as a custom project.

Want new features? Just reply with requests like:
- "Add a music playback mode with real song clips"
- "Add parametric EQ with draggable nodes"
- "Include a visual frequency analyzer"
- "Add more difficulty levels or timed challenges"
- "Export training logs"

I'm ready to iterate and improve this with you!

---

*Train hard. Mix better.* 🎹