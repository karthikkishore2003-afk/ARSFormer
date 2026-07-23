# ARSFormer

Transformer-based semantic segmentation framework for pothole detection and road damage severity assessment.

## Overview

ARSFormer is a transformer-based semantic segmentation model designed for accurate pothole detection and severity assessment from road images. The model integrates a MiT-B2 Transformer Encoder with a custom Feature Pyramid Network (FPN) decoder and a hybrid boundary-aware loss to improve segmentation accuracy.

## Features

- Transformer-based semantic segmentation
- Custom FPN decoder
- Boundary-aware hybrid loss
- Automatic pothole severity estimation
- Road condition assessment
- Interactive visualization of predictions

## Dataset

The model was trained on a curated dataset of 2,170 annotated road images collected from multiple public datasets and manually annotated using CVAT.

## Performance

| Metric | Score |
|--------|-------|
| IoU | 88.83% |
| Dice Score | 94.08% |
| Precision | 94.36% |
| Recall | 92.77% |
| F1-Score | 93.56% |

## Technologies

- Python
- PyTorch
- OpenCV
- Albumentations
- SegFormer
- MiT-B2
- CVAT

## Repository Structure

Coming Soon

## Results

Prediction results and architecture diagrams are available in the **images/** folder.

## Research

An IEEE-format research manuscript has been prepared based on this work.

## Author

Karthik K Kishore
