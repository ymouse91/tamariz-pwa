# Tamariz Statistics

**Tamariz Statistics** is a Progressive Web App (PWA) built for ACAAN-based card trick analysis. It leverages a custom-built double Mnemonica stack and lets you explore valid card locations based on distribution rules.

## 📱 Features

- Fully responsive UI, mobile-optimized for iPhone
- Offline functionality via service worker
- PWA installable on iOS/Android as a fullscreen app
- Scientific styling using Georgia and monospace fonts
- Card symbols rendered with color (♥ ♦ red, ♠ ♣ black)
- Three randomized interaction modes:
  - Randomize (card and location)
  - New card (same location)
  - New location (same card)
- Tuplapakka logic using interleaved Faro shuffle

## 📦 Files

- `index.html` — main application page
- `manifest.json` — PWA metadata
- `service-worker.js` — caching and offline support
- `icon-192.png` / `icon-512.png` — app icons

## 🚀 Usage

1. Deploy the files to GitHub Pages or your own server.
2. Open the site in Safari on iPhone.
3. Tap "Share" → "Add to Home Screen" to install as PWA.
4. Launch the app from home screen in full-screen mode.

## 🔬 Credits

Built with ❤️ by a curious developer exploring the mathematics of magic.
Inspired by Juan Tamariz's Mnemonica stack.
