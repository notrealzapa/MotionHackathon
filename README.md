# Yoga Pose Identifier and Gamification using MediaPipe

Welcome to the Yoga Pose Identifier! This project uses [MediaPipe](https://mediapipe.dev/) to detect and classify yoga poses in real-time. The system not only recognizes the pose but also gamifies the experience by providing real-time feedback and scoring based on the accuracy of the pose.

<img width="825" alt="Screenshot 2024-08-09 at 18 41 23" src="https://github.com/user-attachments/assets/6709c6d0-0602-4580-8f4a-d892bd9d6bc4">

## Overview
This project leverages the power of MediaPipe's pose estimation technology to track and evaluate yoga poses. The system can:

<img width="792" alt="Screenshot 2024-08-09 at 18 48 52" src="https://github.com/user-attachments/assets/927da0d6-60bd-4487-bf8b-d2c05182184b">

1. **Identify Yoga Poses**: Detects common yoga poses such as the "Tree" and "Goddess" poses by comparing live camera input or images against pre-trained reference poses.
2. **Provide Real-Time Feedback**: Offers real-time feedback on the accuracy of the pose, with a score and streak system to gamify the experience.
3. **Custom Pose Training**: Allows for training on custom poses using reference `.npy` files that store the landmarks of correctly performed poses.

## Features

- **Pose Classification**: Compares the user's pose to reference poses (e.g., "Tree", "Goddess") and provides immediate feedback.
- **Gamification**: Adds a score and streak mechanism to encourage correct pose maintenance and improvement.
- **Visualization**: Displays the pose landmarks on the user's image, helping them visualize how well they are matching the reference pose.

