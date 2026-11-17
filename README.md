# Screen Studio

Arabic RTL browser-based screen recorder and screenshot tool.

Developer: [@ahdevloper](https://github.com/ahdevloper)

## Features
- Screen, window, or tab capture where supported by the browser.
- Pause, resume, and stop recording.
- Optional system audio and microphone capture.
- PNG, JPG, and WebP screenshots.
- Responsive desktop, tablet, and mobile layout.
- Local browser settings; no upload backend.

## Run locally
```bash
python -m http.server 8000
```
Open http://localhost:8000.

## Limitations
Video recording currently exports WebM. MP4, MP3, and WAV conversion are not implemented. Screen capture depends on browser/OS support and requires HTTPS or localhost. iOS/iPadOS browser screen capture is restricted; use the device's built-in screen recorder where needed.

MIT License. See LICENSE.