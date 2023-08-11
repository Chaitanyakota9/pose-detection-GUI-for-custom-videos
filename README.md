# Pose Detection GUI for Custom Videos

This repository contains a simple graphical user interface (GUI) application built using Python's Tkinter library for pose detection in custom videos. The application utilizes the MediaPipe library for pose estimation and visualization.

## Features

- Load a custom video for pose detection.
- Visualize detected pose landmarks and connections.
- Display real-time frame rate (FPS) information.

## Prerequisites

Before running the application, ensure you have the following dependencies installed:

- Python 3.6 or higher
- OpenCV (`opencv-python`)
- MediaPipe (`mediapipe`)
- Tkinter (usually included with Python installations)

You can install the required packages using the following command:

pip install opencv-python mediapipe

Getting Started 😁

Clone this repository to your local machine:
git clone https://github.com/Chaitanyakota9/pose-detection-GUI-for-custom-videos.git


Usage:
1. Upon running the application, a window will appear with a title label and buttons.
2. Click the "Open Video" button to select a custom video file (e.g., .mp4).
3. Once the video is loaded, the title label will disappear, and the pose detection processing will start.
4. You will see the video frames with detected pose landmarks and connections.
5. The real-time frame rate (FPS) will be displayed at the top left corner of the video display.
6. To stop processing, click the "Stop Processing" button.


Contributions:

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to create an issue or submit a pull request.
