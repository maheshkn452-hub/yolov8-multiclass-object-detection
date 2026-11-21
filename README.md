# YOLOv8 Multiple Class Object Detection

> **Status:** Completed — Training pipeline, evaluation metrics, and sample inference results included.

## Overview
An end-to-end multi-class object detection pipeline built with **Ultralytics YOLOv8**. This project covers custom dataset configuration, model training, validation metric analysis, and visual inference on unseen test samples.

## Tech Stack
* **Model Architecture:** YOLOv8 (Ultralytics)
* **Frameworks & Libraries:** Python, PyTorch, OpenCV, NumPy, Matplotlib

## Repository Contents
* `notebooks/` / scripts — Model training, validation, and inference workflows
* `data.yaml` — Multi-class dataset configuration and class definitions
* `results/` — Training loss curves, confusion matrix, precision-recall curves, and annotated sample detections

## Key Highlights
* Configured multi-class detection training and hyperparameter tuning in YOLOv8
* Evaluated detection accuracy across classes using mAP@50, mAP@50-95, precision, and recall metrics
* Generated visual bounding-box inference outputs on test images
