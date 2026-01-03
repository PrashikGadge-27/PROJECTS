# Hand Gesture Volume Control 🎚️✋

This project uses **Computer Vision** and **Hand Tracking** to control the system volume using hand gestures captured from a webcam. The distance between your **thumb tip** and **index finger tip** determines the volume level.

---

## Features

- Real-time hand tracking using MediaPipe
- System volume control using PyCaw
- Smooth volume adjustment
- Visual feedback with hand landmarks
- Uses a standard webcam

---

## How It Works

1. Webcam captures live video.
2. MediaPipe detects hand landmarks.
3. Distance between:
   - Thumb tip (Landmark 4)
   - Index finger tip (Landmark 8)
4. Distance is mapped to system volume range.
5. Fingers closer → lower volume  
   Fingers farther apart → higher volume

---

## Requirements

Install the required Python libraries:

```bash
pip install opencv-python mediapipe numpy pycaw comtypes
