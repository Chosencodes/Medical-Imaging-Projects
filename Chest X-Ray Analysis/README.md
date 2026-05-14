# Project 1 — Chest X-Ray Analysis

## Overview
This project applies classical computer vision techniques to chest X-ray scans
using OpenCV and Python. It forms part of a medical radiological AI learning
pipeline, focusing on image preprocessing, contrast enhancement, and structure
detection on thoracic imaging data.

## Dataset
NIH Chest X-Ray Dataset
Source: kaggle.com/datasets/nih-chest-xrays/data
Total images: 112,120 chest X-rays from 30,805 unique patients
Labels: 14 disease classes + No Finding
Format: PNG 1024x1024
License: CC0 Public Domain

## Disease Classes in Dataset
Atelectasis, Consolidation, Infiltration, Pneumothorax, Edema, Emphysema,
Fibrosis, Effusion, Pneumonia, Pleural Thickening, Cardiomegaly,
Nodule, Mass, Hernia, No Finding

## Techniques Used
- Grayscale conversion
- CLAHE contrast enhancement
- Binary thresholding
- Morphological operations (opening & closing)
- Canny edge detection
- Contour detection and drawing

## Project Structure
project1_chest_xray_analysis/
├── data/
├── project1_chest_xray_analysis.ipynb
└── README.md

## Libraries Required
pip install opencv-python numpy matplotlib

## How to Run
1. Clone the repo
2. Download images from kaggle.com/datasets/nih-chest-xrays/data
3. Add your chosen images to the data/ folder
4. Open project1_chest_xray_analysis.ipynb in Jupyter
5. Run all cells

## Results
Each stage of processing is displayed side by side:
- Original scan
- CLAHE enhanced image
- Thresholded image
- Canny edge detected image
- Contours drawn over original

## Key Observations
- Image 1 — Lateral overexposed scan, CLAHE used to recover detail
- Image 2 — Clean frontal scan, lung bounding boxes detected
- Image 3 — Possible cardiomegaly, cardiothoracic ratio calculated
- Image 4 — Lateral scan, rib lines detected using HoughLinesP
- Image 5 — Frontal scan, left vs right lung area comparison
- Image 6 — Lateral scan with medical device highlighted

## Author
Your Name — Medical Radiological AI Learning Journey