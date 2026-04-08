# Hand Tracking - Elastic Strings

A real-time hand-tracking experience that runs entirely in your browser. No installs, no frameworks — just open the file and use your hands.

## Demo

Elastic strings stretch between your fingertips, react to tension, and connect across both hands — all tracked live via your webcam.

## Features

- **Elastic Strings** — glowing bands connect your fingertips, sag with gravity, and turn red when stretched
- **Finger Web** — cat's cradle style mesh connecting all fingertips
- **Light Trails** — colored trails follow each fingertip as you move
- **Particle Burst** — particles emit from your fingertips with gravity physics
- Supports **two hands** with cross-hand string connections
- Mirrored camera so movement feels natural

## How to Use

1. Download `hand-tracking-strings.html`
2. Open it in **Chrome** (recommended for camera access on local files)
3. Allow camera access when prompted
4. Show your hands to the camera and interact

> Requires an internet connection on first load to fetch the MediaPipe model.

## Built With

- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands) — real-time hand landmark detection
- HTML5 Canvas — rendering and visual effects
- Vanilla JavaScript — no frameworks

## Browser Support

| Browser | Works |
|---------|-------|
| Chrome | ✅ Recommended |
| Edge | ✅ |
| Firefox | ⚠️ May block camera on local files |
| Safari | ⚠️ May block camera on local files |
