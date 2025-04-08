# Hand Gesture Mouse Controller

This project allows you to control your mouse using hand gestures with a webcam! It uses real-time hand tracking to enable gesture-based interactions such as cursor movement, left/right clicks, double clicks, and even screenshots — all with simple finger movements.

## Features

- **Cursor Movement**: Cross the thumb with either index or middle finger to move the cursor.
- **Left Click**: Bend the index finger while thumb and index are apart.
- **Right Click**: Bend the middle finger while thumb and middle are apart.
- **Double Click**: Bend both index and middle fingers together.
- **Screenshot**: Bend both fingers while touching the thumb.

## Tech Stack

- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- Pynput

## How It Works

1. Uses MediaPipe to detect and track hand landmarks.
2. Analyzes specific finger angles and distances to recognize gestures.
3. Executes corresponding mouse actions using PyAutoGUI and Pynput.

---

>  Ensure camera permissions are enabled.  
>  Works best on desktop environments with a physical webcam.

