# Hand Gesture Volume Control App

A Streamlit app that uses webcam-based hand gesture recognition to control system volume.

## Features
- Uses OpenCV and MediaPipe for hand detection.
- Streamlit WebRTC to show webcam feed in browser.
- Detects thumb-index finger distance to determine volume.
- Pinky gesture to activate volume setting.

## Installation

```bash
pip install -r requirements.txt
```

## Running the App

```bash
streamlit run app.py
```

## Notes
- Ensure webcam access is allowed.
- Works best on macOS for volume control via `osascript`.
- For other OS, system volume control logic may need to be adapted.
