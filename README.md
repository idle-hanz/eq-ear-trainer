# EQ Ear Trainer

**Master your ears for professional mixing and music production.**

An interactive, browser-based ear training tool focused on audio equalization (EQ). Use real-time Web Audio API to practice identifying frequency bands and matching EQ curves by ear.

## 🎯 Features

- **Frequency Identification Game**: A random EQ band is boosted — listen and guess which frequency range it is!
  - Now with proper **band isolation** (narrow bandpass + controllable surrounding noise level). Low masking = the band stands out clearly. Raise the slider for more realistic "surrounding noise" as your accuracy improves.
- **Corrective EQ (Production Mode)**: Load your own WAV stems (kick, bass, vocal, etc.) or full mixes. The app applies realistic problems. Fix them by ear using full parametric controls (Gain + Q). Includes masking from other stems (not fake noise) for progression and a live EQ curve visualizer. Dual live spectrum analysers (Problem defect reference on left, current output on right) help you connect what you hear to what you see in the frequency domain.
- **Realistic Audio Engine**: Web Audio API (bandpass for isolation + peaking filters). Supports real audio files alongside noise.
- **Progress Tracking**: Streaks, accuracy %, session stats. Local storage saves your best scores (ID game + best corrective accuracy).
- **Fully Responsive**: Beautiful dark UI works perfectly on desktop, tablet, and mobile.
- **Zero Dependencies**: Pure HTML + Tailwind + Vanilla JS. Runs instantly in any modern browser.

## 🚀 Quick Start

1. Visit the live site (after GitHub Pages is enabled): https://idle-hanz.github.io/eq-ear-trainer/
2. Put on headphones for best results.
3. Choose a training mode and start improving your frequency recognition!

## 🎧 How It Works

The app now supports loading your own WAV files (stems or full mixes) for corrective EQ training. For the ID game it uses narrow bandpass isolation + variable masking noise. The main training mode focuses on diagnosing and fixing realistic problems on real audio using proper parametric controls (including Q).

This provides much clearer transfer to actual music production work.

**Pro Tip**: Train 10–15 minutes daily. You'll notice huge improvements in your mixing decisions within a week!

## 🔧 Tech Stack

- HTML5 Web Audio API (BiquadFilterNode: bandpass for isolation + peaking)
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