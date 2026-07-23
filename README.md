# ARSFormer

Transformer-based semantic segmentation framework for pothole detection and road damage severity assessment.

---

## Overview

ARSFormer is a transformer-based semantic segmentation model developed for accurate pothole detection and severity assessment from road images. It combines a MiT-B2 Transformer Encoder with a custom Feature Pyramid Network (FPN) decoder and a boundary-aware hybrid loss to improve segmentation performance.

---

## Features

- Transformer-based semantic segmentation
- Custom FPN decoder
- Hybrid boundary-aware loss
- Automatic pothole severity estimation
- Road condition assessment
- Pixel-level segmentation masks
- Interactive visualization dashboard

---

## Model Architecture

![Architecture](images/architecture.png)

---

## Sample Prediction

![Prediction](images/prediction1.png)

---

## Ground Truth vs Prediction

![Comparison](images/comparison.png)

---

## Training Curve

![Training](images/training_curve.png)

---

## Performance

| Metric | Score |
|---------|--------|
| IoU | 88.83% |
| Dice Score | 94.08% |
| Precision | 94.36% |
| Recall | 92.77% |
| F1-Score | 93.56% |

---

## Dataset

- Total Images: 2,170
- Pixel-level annotations using CVAT
- Multi-source road damage dataset

---

## Technologies Used

- Python
- PyTorch
- OpenCV
- Albumentations
- NumPy
- Pandas
- SegFormer
- MiT-B2
- CVAT

---

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/ARSFormer.git
cd ARSFormer
pip install -r requirements.txt
```

---

## Repository Structure

```
ARSFormer
│
├── images/
├── ARSFormer_GitHub.ipynb
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

## Research

An IEEE-format research manuscript has been prepared based on this work.

---

## Author

**Karthik K Kishore**

M.Sc. Computer Science  
Computer Vision & Deep Learning
