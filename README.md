# YOLOv8-Pose-Detection-and-Keypoint-Angle-Calculation

## Project Overview

This project demonstrates how to use the YOLOv8 model for pose detection on video frames and calculates the angle between three detected keypoints. The project utilizes the **YOLOv8n** model for human pose estimation and then processes the detected keypoints to calculate angles between body joints. This can be useful for applications like posture analysis, fitness tracking, and sports movement analysis.

### Key Features
- **YOLOv8 Pose Detection**: Detects keypoints from video frames using a pre-trained YOLOv8n model.
- **Keypoint Processing**: Extracts keypoints from each frame and calculates angles between them.
- **Angle Calculation**: Uses vector mathematics to calculate the angle between three keypoints (joints).

---

## Setup and Installation

### Requirements

Make sure you have the following packages installed:

```bash
pip install ultralytics
pip install opencv-python-headless
pip install numpy
