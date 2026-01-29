# Crack Detection in Concrete Using Deep Learning

## 📌 Overview
Cracks in concrete structures can indicate serious structural issues if not detected early.
This project uses **deep learning and computer vision** to automatically detect cracks on concrete surfaces from images.

A **ResNet-18 based image classification model** is trained to classify images as *Crack* or *No Crack*, and **Grad-CAM** is used to visually interpret the model’s predictions.

---

## 🎯 Objectives
- Detect surface cracks in concrete using image data
- Achieve high classification accuracy using deep learning
- Provide visual explanation of predictions using Grad-CAM
- Enable simple image upload–based testing

---

## 🧠 Model & Methodology
- **Model:** ResNet-18 (pretrained, fine-tuned)
- **Framework:** PyTorch
- **Task:** Binary image classification (Crack / No Crack)
- **Explainability:** Grad-CAM for highlighting crack regions
- **Interface:** Simple image upload–based testing (local)

---

## 📊 Dataset
- **Type:** Image dataset
- **Classes:**  
  - Crack  
  - No Crack
- **Domain:** Concrete surface images  
- **Preprocessing:**  
  - Image resizing  
  - Normalization  
  - Data augmentation

---

## 📈 Results
- **Accuracy:** **95.7%**
- The model reliably detects visible cracks
- Grad-CAM highlights crack-prone regions, improving interpretability

---

## 🔍 Visual Interpretation (Grad-CAM)
Grad-CAM is used to:
- Understand model decision regions
- Highlight crack-affected areas
- Improve trust and explainability of predictions

---

## 🛠️ Technologies Used
- Python
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- Grad-CAM

