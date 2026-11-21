# YOLOv8 Multiple Class Object Detection

> **Status:** Completed — Training pipeline, evaluation metrics, and sample inference results included.

## Overview
An end-to-end multi-class object detection pipeline built with **Ultralytics YOLOv8**. This project covers custom dataset configuration, model training, validation metric analysis, and visual inference on unseen test samples.

## Tech Stack
* **Model Architecture:** YOLOv8 (Ultralytics)
* **Frameworks & Libraries:** Python, PyTorch, OpenCV, NumPy, Matplotlib

## Dataset

* **Classes (`3`):** `Zebra`, `Elephant`, `Dog` (annotated in YOLOv8 bounding-box format, adhering to the `≤ 25%` object-to-image area constraint).
* **Included in Repo:** `valid/`, `test/`, and `data.yaml` are included directly so inference and evaluation run out of the box.
* **Training Split (`train/`):** Excluded from Git due to repository size limits. Download the full dataset in YOLOv8 format from [Roboflow](https://universe.roboflow.com/maheshs-workspace-slzdj/object-detection-bc78o/dataset/1) and place the `train/` folder in the project root before re-training.

## Repository Contents
* `notebooks/` / scripts — Model training, validation, and inference workflows
* `data.yaml` — Multi-class dataset configuration and class definitions
* `results/` — Training loss curves, confusion matrix, precision-recall curves, and annotated sample detections

## Key Highlights
* Configured multi-class detection training and hyperparameter tuning in YOLOv8
* Evaluated detection accuracy across classes using mAP@50, mAP@50-95, precision, and recall metrics
* Generated visual bounding-box inference outputs on test images
