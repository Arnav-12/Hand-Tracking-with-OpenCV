# Hand Tracking with OpenCV and MediaPipe

## Overview
This project implements real-time hand tracking using OpenCV and MediaPipe. It detects hands from a webcam feed, identifies hand landmarks, and tracks hand movements. The project is modularized for easy use and customization.

## Features
- Real-time hand detection using MediaPipe
- Landmark identification and tracking
- Modular implementation for easy integration
- FPS (Frames Per Second) display for performance monitoring

## Requirements
Ensure you have Python installed along with the following dependencies:

```bash
pip install opencv-python mediapipe
```

## File Structure
- `Basics.py` – A basic hand tracking script.
- `HandTrackingModule.py` – A modularized version for easy reuse.
- `ProjectExample.py` – Example usage of `HandTrackingModule.py`.

## Usage
### Running the Basic Script
To test basic hand tracking:
```bash
python Basics.py
```

### Using the Hand Tracking Module
To use the modularized hand detector:
```bash
python ProjectExample.py
```

## How It Works
1. The webcam feed is captured using OpenCV (`cv2.VideoCapture(1)`).
2. Frames are processed with MediaPipe to detect hands.
3. Detected hand landmarks are drawn on the image.
4. Landmark positions are extracted and printed.
5. The frame rate is calculated and displayed.

## Example Output
When running the scripts, a window will display the video feed with detected hands and landmarks drawn on it.



