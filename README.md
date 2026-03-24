# AI Stage Mirror

Real-time mouth symmetry trainer for speakers and performers. Uses your webcam and MediaPipe Face Mesh (468 3D face landmarks) to detect asymmetry and give instant visual feedback.

**[Try it live](https://rai220.github.io/ai-stage-mirror/)**

## What it does

- Tracks 468 face landmarks via webcam in real-time
- Computes a composite symmetry score from three metrics: corner distance from nose (30%), left/right opening height (50%), and vertical corner offset (20%)
- Highlights the weaker side with color-coded feedback (green/yellow/red)
- Shows a zoomed mouth diagram with symmetry midline
- Adjustable sensitivity threshold
- Built-in exercises: free monitoring, slow opening, vowels, smile

## How to use

1. Open `index.html` in a browser (or use the live link above)
2. Click **Start Camera** and allow access
3. Wait ~15 seconds for the model to load
4. Speak or do exercises — asymmetry is shown in real-time

## Tech

- [MediaPipe Face Mesh](https://google.github.io/mediapipe/solutions/face_mesh.html) via CDN
- Vanilla JS + Canvas API
- Zero build dependencies — single HTML file, runs directly in browser

## License

MIT
