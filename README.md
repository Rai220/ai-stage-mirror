# AI Stage Mirror

AI-powered training tool for speakers and performers. Analyzes facial expressions via webcam and provides real-time feedback.

## Features

- **Mouth Symmetry** — tracks asymmetry during speech, highlights the weaker side with actionable feedback
- *(coming soon)* Posture, gestures, eye contact, diction analysis

## Tech

- [MediaPipe Face Mesh](https://google.github.io/mediapipe/solutions/face_mesh.html) — 468 3D face landmarks from a regular webcam
- Vanilla JS, Canvas API
- Zero build dependencies — runs directly in the browser

## Getting Started

```bash
# Simply open in browser:
open index.html

# Or via local server (recommended for HTTPS/camera):
npx serve .
```

## How to Use

1. Click "Start Camera" and allow access
2. Wait 10-20 seconds for model to load
3. Center your face in the frame
4. Speak or do exercises — the app will show asymmetry in real-time

## Exercises

1. **Free Monitoring** — speak naturally
2. **Slow Opening** — open mouth slowly
3. **Vowels A-O-U** — pronounce vowels maintaining symmetry
4. **Smile** — practice a symmetrical smile

## License

MIT
