# Yoga Pose Identifier and Gamification using MediaPipe

Welcome to the Yoga Pose Identifier! This project uses [MediaPipe](https://mediapipe.dev/) to detect and classify yoga poses in real-time. The system not only recognizes the pose but also gamifies the experience by providing real-time feedback and scoring based on the accuracy of the pose.

## Overview

This project leverages the power of MediaPipe's pose estimation technology to track and evaluate yoga poses. The system can:

1. **Identify Yoga Poses**: Detects common yoga poses such as the "Tree" and "Goddess" poses by comparing live camera input or images against pre-trained reference poses.
2. **Provide Real-Time Feedback**: Offers real-time feedback on the accuracy of the pose, with a score and streak system to gamify the experience.
3. **Custom Pose Training**: Allows for training on custom poses using reference `.npy` files that store the landmarks of correctly performed poses.

## Features

- **Real-Time Pose Detection**: Using a webcam, the system captures frames and analyzes the user's pose in real-time.
- **Pose Classification**: Compares the user's pose to reference poses (e.g., "Tree", "Goddess") and provides immediate feedback.
- **Gamification**: Adds a score and streak mechanism to encourage correct pose maintenance and improvement.
- **Visualization**: Displays the pose landmarks on the user's image, helping them visualize how well they are matching the reference pose.

## Installation

To run this project locally, you'll need to install the required packages:

```bash
pip install mediapipe opencv-python
