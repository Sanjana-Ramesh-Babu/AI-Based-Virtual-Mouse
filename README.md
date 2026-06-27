# AI Virtual Mouse using Computer Vision

Control your computer mouse using hand gestures captured through a webcam. This project uses Computer Vision and Hand Tracking to move the mouse cursor and perform click operations without requiring a physical mouse.

---

## Overview

The AI Virtual Mouse is a real-time computer vision application that detects hand landmarks using MediaPipe and controls the system cursor through OpenCV and PyAutoGUI.

The project tracks the index finger to move the cursor and detects the distance between the thumb and index finger to perform mouse click actions.

---

## Features

- Real-time hand tracking
- Cursor movement using index finger
- Click operation using thumb and index finger gesture
- Webcam-based interaction
- Lightweight and fast implementation
- Touch-free mouse control

---

## Tech Stack

- Python
- OpenCV
- MediaPipe
- PyAutoGUI

---

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Virtual-Mouse.git
cd Virtual-Mouse
```

### Install dependencies

```bash
pip install opencv-python mediapipe pyautogui
```

or

```bash
pip install -r requirements.txt
```

---

## Run the Project

```bash
python main.py
```

Allow webcam access when prompted.

---

## How It Works

1. Opens the webcam using OpenCV.
2. Detects the user's hand using MediaPipe.
3. Identifies the index fingertip landmark.
4. Maps finger coordinates to screen coordinates.
5. Moves the system cursor based on finger movement.
6. Detects when the thumb and index finger come close together.
7. Performs a mouse click using PyAutoGUI.

---

## Working

- Move your **index finger** to move the cursor.
- Bring your **thumb and index finger together** to perform a click.

---

## Dependencies

- OpenCV
- MediaPipe
- PyAutoGUI

Install them using:

```bash
pip install opencv-python mediapipe pyautogui
```

---

## Future Improvements

- Right-click gesture
- Double-click gesture
- Drag and drop functionality
- Scrolling using hand gestures
- Multi-hand gesture support
- Gesture customization

---

## Applications

- Touch-free computer interaction
- Smart presentations
- Accessibility assistance
- Human-Computer Interaction (HCI)
- Gesture-controlled systems

---

## Author

**Sanjana R**

B.Tech Computer Science Engineering  
SRM Institute of Science and Technology

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub!
