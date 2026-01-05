# kidney-ct-classification

Deep Learning–based Detection and Classification of Kidney Abnormalities  
(Normal, Cyst, Stone, Tumor) from CT Scans

---

## 📌 Project Overview
This repository contains the implementation for the MSc Data Science final project:

**Detection and Classification of Kidney Abnormalities from CT Scans Using Deep Learning**

The project applies transfer learning–based convolutional neural networks (CNNs) to classify kidney CT images into four clinically relevant categories:
- Normal
- Cyst
- Stone
- Tumor

The objective is to compare lightweight and high-performance CNN architectures in terms of accuracy, robustness, and computational efficiency, while maintaining model interpretability.

---

## 🧠 Models Implemented
- **MobileNetV2** – lightweight and computationally efficient baseline  
- **DenseNet121** – deep feature reuse with strong representational capacity  
- **EfficientNet-B0** – balanced accuracy–efficiency trade-off (best performer)

---

## 📂 Dataset
The project uses the **CT Kidney Dataset: Normal–Cyst–Tumor and Stone** from Kaggle.

- Total images: 12,446 CT slices  
- Modality: 2D CT images  
- Source: Hospital PACS systems, Dhaka, Bangladesh  

Dataset link:  
https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone

> The dataset is fully anonymised and used strictly for academic research.

---

## ⚙️ Methodology Summary
- Image preprocessing (noise reduction, contrast enhancement, normalisation)
- Train / validation / test split
- Transfer learning with pretrained CNNs
- Performance evaluation using accuracy, precision, recall, F1-score
- Model interpretability using Grad-CAM visualisations

---

## 📊 Key Results
- **EfficientNet-B0** achieved the highest test accuracy and balanced class-wise performance
- **DenseNet121** showed competitive accuracy with higher training instability
- **MobileNetV2** provided a fast and efficient baseline

---

## 🧪 Reproducibility
All experiments were conducted using PyTorch.  
Trained model weights are provided for reproducibility.

Recommended environment: **Google Colab (GPU)**

---

## ⚖️ Ethics Statement
This study uses secondary, anonymised data.  
No human participants were involved, and no ethical approval was required.

---

## 🎓 Academic Context
MSc Data Science Final Project  
University of Hertfordshire  
Module: **7PAM2002**

---

## 👤 Author
**Name:** SAINITHISH BILLAKANTI  
**Student ID:** 23091029  

---

## 📜 License
This repository is for academic and educational use only.  
Dataset rights belong to the original authors.
