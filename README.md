# Medical Imaging Projects

A portfolio of medical image processing and AI projects built using 
Python, OpenCV, PyTorch and pydicom on real clinical datasets.
Each project applies computer vision and deep learning techniques 
to real radiological imaging problems.

---

## Projects

### 1. Chest X-Ray Analysis
Classical computer vision pipeline applied to chest X-rays from 
the NIH Chest X-Ray Dataset (112,120 images, 14 disease classes).

**Techniques:** CLAHE contrast enhancement, thresholding, 
morphological operations, Canny edge detection, contour detection, 
cardiothoracic ratio computation, foreign body artefact detection, 
HoughLinesP spine detection

**Dataset:** NIH Chest X-Ray Dataset — kaggle.com/datasets/nih-chest-xrays/data

**Clinical Findings Explored:** Cardiomegaly, pleural effusion, 
pulmonary venous congestion, foreign body artefacts

---

### 2. Bone Fracture X-Ray Edge Detection
Edge detection and boundary analysis applied to bone fracture 
X-rays across multiple body regions.

**Techniques:** Gaussian blur, Canny edge detection, morphological 
operations, contour detection, bounding box localization

**Dataset:** FracAtlas — Bone Fracture Multi-Region X-Ray Dataset
kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data

**Body Regions:** Hand, Hip, Leg, Shoulder

---

### 3. Pneumonia X-Ray Analysis
Detection and localization of pneumonia opacity regions in 
chest X-rays using classical image processing techniques.

**Techniques:** Thresholding, morphological operations, 
contour detection, bounding box localization

**Dataset:** RSNA Pneumonia Detection Dataset

---

### 4. Classwork
Practice notebooks covering foundational computer vision and 
deep learning concepts applied to medical imaging contexts.

**Topics Covered:**
- Bounding box detection and area calculation
- HoughLinesP line detection
- Tensor operations in PyTorch
- DICOM file reading and processing with pydicom
- Image normalization and preprocessing

---

## Tech Stack

- Python 3.9
- OpenCV 4.5
- PyTorch
- pydicom
- NumPy
- Matplotlib
- Pandas
- Jupyter Notebook

---

## Datasets Used

| Dataset | Source | Images |
|---|---|---|
| NIH Chest X-Ray | Kaggle | 112,120 |
| FracAtlas | Kaggle | 4,083 |
| RSNA Pneumonia | Kaggle | 26,684 |

---

## Clinical Background

These projects are built by someone with a Bachelor of Science 
in Anatomy, combining clinical domain knowledge with applied 
computer vision techniques. Each project includes clinical 
context and observations written in notebook markdown, 
reflecting both the technical implementation and the 
radiological significance of the findings.

---

## Author

**Chosen Nosakhanoze Otabor**
BSc Anatomy — Ambrose Alli University
Medical Radiological AI Researcher

GitHub: github.com/Chosencodes
LinkedIn: linkedin.com/in/chosen-otabor-938938256
Email: otaborchoosen1@gmail.com

---

## Roadmap

- [x] Chest X-Ray preprocessing pipeline
- [x] Bone fracture edge detection
- [x] Pneumonia region analysis
- [x] DICOM file processing
- [ ] Brain MRI tumor segmentation
- [ ] Retinal vessel detection
- [ ] Deep learning classification with PyTorch
- [ ] U-Net segmentation with MONAI
- [ ] Full end-to-end medical AI pipeline