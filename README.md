# Computer Vision Projects

This repository showcases a set of practical Computer Vision implementations covering **object detection, image classification, and semantic segmentation**. Each project demonstrates end-to-end pipelines including dataset handling, model training, evaluation, and inference.

---

## 🚀 Projects Overview

### 1. Drone Landing Pad Detection (YOLOv8)

**File:** `yolov8_drone_landing_pad_detection.ipynb`

This project focuses on detecting drone landing pads using the YOLOv8 object detection framework.

**Key Work:**

* Dataset acquisition using Roboflow
* Training YOLOv8 model on custom dataset
* Hyperparameter tuning (epochs, batch size, image size)
* Evaluation using detection metrics
* Testing on sample and real-world images

**Tech Stack:**

* Ultralytics YOLOv8
* OpenCV
* Roboflow

---

### 2. Land Use Classification (EuroSAT Dataset)

**File:** `eurosat_land_use_classification.ipynb`

This project implements image classification on satellite imagery using the EuroSAT dataset.

**Key Work:**

* Dataset loading and preprocessing
* Train-test split (80-20)
* Image transformations (resizing, normalization)
* Model training using PyTorch
* Performance evaluation on unseen data

**Classes Include:**

* Residential, Industrial, Forest, River, Highway, etc.

**Tech Stack:**

* PyTorch
* Torchvision
* Matplotlib

---

### 3. Semantic Segmentation (DeepGlobe Dataset)

**File:** `deepglobe_semantic_segmentation.ipynb`

This project performs pixel-wise classification using semantic segmentation techniques.

**Key Work:**

* Dataset download via KaggleHub
* Image-mask preprocessing
* Train-validation split
* Model training using segmentation architectures
* Evaluation of segmentation outputs

**Applications:**

* Road extraction
* Satellite imagery understanding

**Tech Stack:**

* segmentation-models-pytorch
* Albumentations
* OpenCV
* PyTorch

---

## 🧠 Learning Outcomes

Across these projects, the following concepts were implemented:

* Object Detection using YOLOv8
* Image Classification using CNNs
* Semantic Segmentation pipelines
* Data preprocessing and augmentation
* Model training and evaluation workflows
* Working with real-world datasets (Roboflow, EuroSAT, DeepGlobe)

---

## ⚙️ Setup Instructions

```bash
git clone https://github.com/mihir-mash/Computer-Vision-Assignments.git
cd Computer-Vision-Assignments
pip install -r requirements.txt
jupyter notebook
```

---

## 📌 Notes

* GPU is recommended for training (especially YOLOv8 and segmentation tasks)
* Some datasets are downloaded dynamically inside notebooks
* Each notebook is self-contained and can be run independently

---
