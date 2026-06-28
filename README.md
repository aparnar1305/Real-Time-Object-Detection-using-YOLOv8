# Real-Time Object Detection using YOLOv8

## Overview

This project is an AI-powered real-time object detection system developed using Python, OpenCV, and the Ultralytics YOLOv8 Nano model. The application captures live video from a webcam and detects multiple objects by drawing bounding boxes, displaying object labels, and confidence scores.

## Features

- Real-time webcam object detection
- Detects multiple objects simultaneously
- Displays object labels and confidence scores
- Uses the lightweight YOLOv8 Nano model
- Beginner-friendly implementation

## About the Model

This project uses the pre-trained **YOLOv8 Nano (yolov8n.pt)** model provided by Ultralytics. The model is trained on the **COCO (Common Objects in Context)** dataset, which contains 80 everyday object classes such as person, laptop, bottle, chair, keyboard, cell phone, dog, cat, and many more.

## Technologies Used

- Python
- OpenCV
- Ultralytics YOLOv8
- COCO Dataset (Pre-trained Model)

## Installation

```bash
pip install ultralytics opencv-python
```

## Run

```bash
python YOLO.py
```

Press **Q** to quit the application.
