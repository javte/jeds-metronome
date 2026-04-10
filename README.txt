# Metronome PWA — iPhone Install Guide

## How to install on your iPhone

This is a Progressive Web App (PWA) — it works like a native app once installed.

### Step 1: Host the files
You need to serve these files over HTTPS. The easiest free options:

**Option A — GitHub Pages (recommended, free)**
1. Create a free GitHub account at github.com
2. Create a new repository (e.g. "my-metronome"), set it to Public
3. Upload all 4 files: index.html, sw.js, manifest.json, icon.svg
4. Go to Settings → Pages → set Source to "main" branch, root folder
5. Your app will be live at: https://yourusername.github.io/my-metronome

**Option B — Netlify (drag & drop, free)**
1. Go to netlify.com and sign up free
2. Drag the entire folder onto their dashboard
3. You'll get a URL like: https://random-name.netlify.app

### Step 2: Open in Safari on iPhone
- Open Safari (must be Safari, not Chrome) and go to your URL

### Step 3: Add to Home Screen
1. Tap the **Share** button (box with arrow pointing up)
2. Scroll down and tap **"Add to Home Screen"**
3. Name it "Metronome" → tap **Add**

The app icon will appear on your home screen. It opens full-screen with no browser chrome, works completely offline, and saves your presets locally on your device.

## Features
- BPM range: 30–300
- Time signatures: 2/4, 3/4, 4/4, 5/4, 6/4, 7/4, 8/4
- 3 sound types: Click, Beep, Wood
- Tap tempo
- Save unlimited song presets with name + BPM
- Tempo name display (Andante, Allegro, etc.)
- Works offline after first load
