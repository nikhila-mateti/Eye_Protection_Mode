# Eye_Protection_Mode

This Python script captures video from webcam, detects faces in real-time, and issues a warning if the detected face is too close to the camera. If the face is within a specified distance, the system will lock the workstation as a warning.

## Features

- Real-time face detection using OpenCV.
- Measures distance based on the face height in pixels.
- Issues a warning by locking the workstation if the face is too close.

## Requirements

- Python 3.x
- OpenCV
- Numpy
