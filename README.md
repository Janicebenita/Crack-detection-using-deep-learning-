# 🚧 AI-Based Concrete Crack Detection System
### Deep Learning + Explainable AI for Automated Infrastructure Inspection

---

## 🚀 Overview

Manual inspection of concrete structures is time-consuming, subjective, and prone to human error.  
This project presents an **AI-powered crack detection system** that automates inspection using deep learning and computer vision.

Built using a fine-tuned **ResNet-18 model**, the system classifies images as **Crack / No Crack** and provides **visual explanations using Grad-CAM**, making predictions interpretable and reliable.

---

## 💡 Key Highlights

- ✅ **95.7% Accuracy** on crack classification  
- ⚡ Reduced manual inspection effort significantly  
- 🧠 Explainable AI using **Grad-CAM visualization**  
- 🏗️ Designed for **real-world infrastructure inspection scenarios**  
- 🔍 Identifies crack regions instead of just predicting labels  

---

## 🎯 Problem Statement

Traditional crack detection methods:
- Require manual inspection by experts  
- Are slow and expensive  
- Lack consistency and scalability  

👉 This system solves these issues using **automated, scalable AI-based inspection**

---

## 🧠 Solution Approach

This project builds an end-to-end pipeline



### 🔧 Model Details
- **Architecture:** ResNet-18 (pretrained, fine-tuned)
- **Task:** Binary Classification (Crack / No Crack)
- **Framework:** PyTorch
- **Explainability:** Grad-CAM

---

## 📊 Results

| Metric        | Value   |
|--------------|--------|
| Accuracy     | 95.7%  |
| Model Type   | CNN (ResNet-18) |
| Output       | Crack / No Crack |

👉 The model performs reliably on real-world crack images and highlights defect regions effectively.

---

## 🔍 Explainability with Grad-CAM

Unlike traditional black-box models, this system provides **visual explanations**:

- Highlights crack-affected regions  
- Improves trust in predictions  
- Assists engineers in validation  

---

## 🖼️ Sample Output

*(Add images here — very important)*

| Input Image | Prediction | Grad-CAM Output |
|------------|-----------|-----------------|
| (image)    | Crack     | (heatmap)       |

---

## 📁 Dataset

- Concrete surface image dataset  
- Classes:
  - Crack  
  - No Crack  

### Preprocessing:
- Image resizing  
- Normalization  
- Data augmentation  

---

## 🛠️ Tech Stack

- Python  
- PyTorch  
- OpenCV  
- NumPy  
- Matplotlib  
- Grad-CAM  

---

## ⚙️ How to Run

```bash
git clone https://github.com/Janicebenita/Crack-detection-using-deep-learning-.git
cd Crack-detection-using-deep-learning-
pip install -r requirements.txt
