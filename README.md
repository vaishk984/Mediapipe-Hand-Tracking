# Mediapipe-Hand-Tracking

**Mediapipe-Hand-Tracking** is a real-time hand tracking application built using [MediaPipe](https://google.github.io/mediapipe/) and OpenCV. It detects hand landmarks from a webcam feed and visualizes them with connections and FPS counter. Ideal for gesture recognition experiments, HCI projects, and real-time vision systems.

---

## Features

- Real-time webcam hand tracking
- Landmark detection for both hands (21 key points each)
- Draws landmarks and hand skeleton
- Displays frames-per-second (FPS)
- Easily extendable for gesture recognition

---
## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/HandPoseVision.git
   cd HandPoseVision

2. Create a virtual environment (recommended):
   ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows: .venv\Scripts\activate

3. Install dependencies
   ```bash
    pip install -r requirements.txt

## Run the App

    ```bash
    python HandTracking.py
# Make sure your webcam is accessible.
# Enter 'q' or close the window to stop.

