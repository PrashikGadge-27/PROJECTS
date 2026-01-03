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


--------------------------------------------------------------------------------------------------hotel.ipynb
# Python Machine Learning & Computer Vision Projects 🚀

This repository contains **two Python projects**:
1. **Hand Gesture Volume Control** using Computer Vision
2. **Restaurant Reviews Sentiment Analysis** using Machine Learning (NLP)

---

# 📌 Project 1: Hand Gesture Volume Control 🎚️✋

Control your system volume using hand gestures captured via a webcam.

---

## 🔹 Description

This project uses **MediaPipe Hand Tracking** to detect hand landmarks and calculates the distance between the **thumb tip** and **index finger tip** to control the system volume in real time.

---

## 🔹 Features

- Real-time hand tracking
- Smooth volume control
- Visual feedback with landmarks
- Uses webcam input
- Windows system volume control

---

## 🔹 Technologies Used

- OpenCV
- MediaPipe
- NumPy
- PyCaw
- Python

---

## 🔹 How It Works

- Webcam captures video
- MediaPipe detects hand landmarks
- Distance between landmarks:
  - Thumb tip → Landmark 4
  - Index finger tip → Landmark 8
- Distance is mapped to system volume range

---

## 🔹 Installation

```bash
pip install opencv-python mediapipe numpy pycaw comtypes
