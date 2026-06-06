# EQ Ear Trainer

**Master your ears for professional mixing and music production.**

An interactive, browser-based ear training tool focused on audio equalization (EQ). Use real-time Web Audio API to practice identifying frequency bands and matching EQ curves by ear.

## 🎯 Features

- **Frequency Identification Game (Game 1)**: Two modes for learning:
  - **Practice mode**: Freely click any band button to hear isolated examples (with adjustable surrounding noise/masking). Great for building familiarity.
  - **Test mode**: Hit "Start 10-Round Test" for a scored quiz. The game runs exactly 10 rounds with auto-advance after each guess. Get a final score (X/10 + percentage) at the end, plus encouragement and "Play Again" option. Includes proper band isolation (narrow bandpass + controllable masking) and helpful frequency range labels (e.g. "Sub Bass 20-60 Hz").
- **Corrective EQ (Production Mode / Game 2)**: Load your own WAV stems (kick, bass, vocal, etc.) or full mixes. The app applies realistic single-band problems based on 6 progressive difficulty levels. Fix (or match) them by ear using full parametric controls (Gain + Q).
  - Two mental models: **Correct mode** (fix the affected track toward clean) and **Match mode** (apply the problem to a clean track).
  - Visual flow indicators appear between the playback buttons and change position depending on the current mode.
  - Dynamic instructions box under the "Other Stems Level" slider that updates with the current level's rules and what you should aim for.
  - Other Stems Level defaults to 0 (no masking) but can be raised for realistic mix context using your other loaded tracks.
  - Live EQ curve visualizer. Sliders show color-coded badges + band names (matching Game 1) + the exact frequency being adjusted.
- **Realistic Audio Engine**: Web Audio API (bandpass for isolation + peaking filters). Supports real audio files alongside noise.
- **Progress Tracking**: Streaks and accuracy for Practice mode in Game 1. Per-test scores in Game 1 Test mode. Local storage saves your stats.
- **Fully Responsive**: Beautiful dark UI works perfectly on desktop, tablet, and mobile.
- **Zero Dependencies**: Pure HTML + Tailwind + Vanilla JS. Runs instantly in any modern browser.

## 🚀 Quick Start

1. Visit the live site (after GitHub Pages is enabled): https://idle-hanz.github.io/eq-ear-trainer/
2. Put on headphones for best results.
3. Choose a training mode and start improving your frequency recognition!

## 🎧 How It Works

The app supports two distinct training experiences:

**Game 1 (Frequency Identification)** uses real-time band isolation via bandpass filters on noise. You can practice by freely listening to any band, or challenge yourself with a structured 10-round scored test. Frequency range labels help connect what you hear to real-world band names.

**Game 2 (Corrective EQ)** lets you load real WAV stems or mixes. Problems are generated according to 6 progressive levels (starting with simple 6 dB narrow boosts and expanding to full ±3/6 dB with narrow/wide Q choices). You work in either Correct mode (fix the affected signal back to clean) or Match mode (recreate the problem on a clean signal). Other loaded stems can be mixed in at low level for realistic masking context.

A live parametric EQ curve and color-coded slider labels (with exact frequencies) help bridge the gap between ear and eye. The goal is direct transfer to using a parametric EQ in a real DAW session.

This design provides much clearer transfer to actual music production work.

**Pro Tip**: Train 10–15 minutes daily. You'll notice huge improvements in your mixing decisions within a week!

## 🔧 Tech Stack

- HTML5 Web Audio API (BiquadFilterNode: bandpass for isolation + peaking filters)
- Tailwind CSS (via CDN)
- Vanilla JavaScript (no build step)

## 🚢 Deployment

This repository is set up for GitHub Pages. To activate:

1. Go to your repo **Settings** → **Pages**
2. Under "Build and deployment" → **Source** → Select **Deploy from a branch**
3. Branch: `main` | Folder: `/ (root)`
4. Save — your site will be live in ~1 minute at the URL above.

## 👏 Credits & Next Steps

Built for you by **Grok** (xAI) as a custom project.

The app is under active development based on your feedback. Current focus areas include clearer mental models between the two games, better labeling, and realistic production-oriented training.

Want new features? Just reply with requests like:
- "Add best-score tracking for the 10-round tests"
- "Support loading full songs instead of just short stems"
- "Add a 'weakness report' after tests"
- "Include pink noise or other masking types"
- "Make the corrective game support two simultaneous bands at higher levels"

I'm ready to iterate and improve this with you!

---

*Train hard. Mix better.* 🎹