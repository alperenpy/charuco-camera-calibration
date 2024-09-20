# charuco-camera-calibration
A Python project for camera calibration using Charuco boards and ArUco markers. This script captures frames from a webcam, detects markers, and calculates camera calibration parameters such as the camera matrix and distortion coefficients.
# Charuco Camera Calibration

This project is designed to calibrate a camera using Charuco boards and ArUco markers. The calibration process helps correct lens distortion, leading to more accurate image captures.

## Features

- Detect ArUco markers from a video feed.
- Interpolate Charuco board corners for more precise calibration.
- Collect calibration data from multiple frames.
- Calculate the camera matrix and distortion coefficients.

## Requirements

- Python 3.x
- OpenCV (with ArUco module)
- NumPy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/alperenpy/charuco-camera-calibration.git
   
2. Install required Python Libraries:
   ```bash
   pip install opencv-python opencv-contrib-python numpy
## Usage
1. Run the script to start detecting markers and calibrating the camera:
   ```bash
   python charuco_calibration.py
2. Press q to exit the capture loop.



