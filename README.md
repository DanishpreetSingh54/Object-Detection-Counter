# Real-Time Object Detection & Counting

A lightweight Computer Vision prototype for detecting and counting objects from a live camera feed using YOLO and OpenCV, with a potential application in logistics and land-port operations.

## Problem Statement

Land ports and logistics facilities handle continuous vehicle movement. Manual monitoring of vehicle activity can be time-consuming, particularly during busy periods.

This project demonstrates how Computer Vision can automatically detect visible objects from a camera feed and provide basic real-time counts.

## Solution

The system captures video frames from a webcam and processes them using a pretrained YOLO model.

Camera
↓
OpenCV Frame Capture
↓
YOLO Object Detection
↓
Bounding Boxes + Confidence
↓
Object Counting
↓
Real-Time Display

## Key Features

- Real-time object detection
- Bounding box visualization
- Confidence scores
- Object-wise counting
- Webcam-based processing
- Logistics/land-port use case

## Technologies & Skills

| Technology | Usage |
| Python | Application logic |
| OpenCV | Video capture and visualization |
| YOLO | Object detection |
| Computer Vision | Image and video analysis |
| Git & GitHub | Version control and project hosting |

## Data

The project uses live webcam frames and does not require a custom dataset. A pretrained YOLO model is used for general object detection.

For a future land-port-specific version, locally collected vehicle images or CCTV footage could be used to improve detection for specific operational environments.

## Land-Port Usage & Solution

The system can be used as a basic real-time vehicle monitoring solution at land-port entry gates, cargo areas, checkpoints, and parking zones. Using a camera feed, it automatically detects and counts visible vehicles such as cars, trucks, and buses, providing quick information about vehicle activity without continuous manual observation. This can support traffic monitoring, operational planning, congestion awareness, and future entry-exit analysis at land ports.

