# Marine Waste Detection Using YOLOv8

A computer vision project that detects marine waste on beach images using YOLOv8 object detection.

## Overview

This project uses deep learning to automatically detect marine debris in beach images. The system was designed to support environmental monitoring and beach cleanliness evaluation.

## Features

- Marine waste detection using YOLOv8
- Bounding box prediction for detected trash
- Beach cleanliness classification
- Google Colab training workflow
- Evaluation using precision, recall, and mAP

## Dataset

The project used the Beach Garbage v2 dataset from Roboflow Universe.

## Model

- YOLOv8s
- Image size: 640x640
- Epochs: 30
- Batch size: 8
- Platform: Google Colab with T4 GPU

## Results

- Precision: 0.89
- Recall: 0.85
- mAP@50: 0.91

## Technologies Used

- Python
- YOLOv8
- Ultralytics
- OpenCV
- Google Colab
- Roboflow
- Matplotlib
- NumPy

  ## Sample Detection Result

The trained YOLOv8 model successfully detects marine waste in beach images and draws bounding boxes around detected objects.

<img width="495" height="497" alt="image" src="https://github.com/user-attachments/assets/58b67035-5f1e-41a2-9152-da4874787434" />


## Project Structure

```text
marine-waste-detection-yolov8/
│
├── README.md
├── marine_waste_detection.ipynb
└── Marine_Waste_Detection_Report.pdf
