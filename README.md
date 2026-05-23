# 🚧 AI-Powered Concrete Crack Detection & Localization System
## 🧠 YOLOv8 + ResNet-18 Hybrid Deep Learning Pipeline with Explainable AI

<div align="center">

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python"/>
<img src="https://img.shields.io/badge/PyTorch-Deep_Learning-red?style=for-the-badge&logo=pytorch"/>
<img src="https://img.shields.io/badge/YOLOv8-Object_Detection-yellow?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ResNet18-Classification_Model-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Explainable_AI-GradCAM-purple?style=for-the-badge"/>
<img src="https://img.shields.io/badge/OpenCV-Computer_Vision-orange?style=for-the-badge&logo=opencv"/>
<img src="https://img.shields.io/badge/Flask-Web_App-black?style=for-the-badge&logo=flask"/>

<br><br>

---

# 📌 Project Overview

Inspection of concrete structures is a critical process in infrastructure maintenance. Traditional manual inspection methods are:

❌ Time-consuming  
❌ Expensive  
❌ Subjective  
❌ Difficult to scale  
❌ Prone to human error  

To address these challenges, this project introduces an **AI-powered hybrid crack detection and localization system** that combines:

✅ YOLOv8 Object Detection  
✅ ResNet-18 Deep Feature Learning  
✅ Explainable AI using Grad-CAM  
✅ Computer Vision Techniques  

The system automatically detects cracks, localizes damaged regions, classifies crack presence, and visually explains model predictions.

---

# 🌟 Key Highlights

<div align="center">

| Feature | Description |
|---|---|
| ✅ Hybrid AI Pipeline | YOLOv8 + ResNet-18 |
| 🎯 Crack Localization | Bounding-box crack detection |
| 🧠 Explainable AI | Grad-CAM visualization |
| ⚡ Automated Inspection | Faster infrastructure analysis |
| 📈 95.7% Accuracy | High-performance crack classification |
| 🌐 Flask-Based Interface | Interactive web application |
| 🏗️ Infrastructure Focused | Real-world engineering use case |

</div>

---

# 🧠 Revised System Workflow

<div align="center">

```text
Input Image
      ↓
Image Preprocessing
      ↓
YOLOv8 + ResNet-18 Hybrid Pipeline
      ↓
Crack Detection + Classification
      ↓
Grad-CAM Explainability
      ↓
Final Crack Visualization
```

</div>

---

# 🖼️ Complete System Architecture

<p align="center">
  <img src="images/architecture_pipeline.png" width="1000"/>
</p>

---

# 🔍 How the System Works

## 📥 1. Input Image
Concrete surface images are uploaded into the system for inspection.

---

## ⚙️ 2. Image Preprocessing

The preprocessing pipeline includes:

- Image Resizing
- Normalization
- Data Augmentation
- Noise Reduction

These steps improve model robustness and detection performance.

---

## 🧠 3. Hybrid Deep Learning Pipeline

### 🔹 YOLOv8 Object Detection

YOLOv8 is used for:

✔️ Crack localization  
✔️ Bounding box generation  
✔️ Multi-crack region detection  

---

### 🔹 ResNet-18 Backbone

ResNet-18 is used for:

✔️ Feature extraction  
✔️ Crack classification  
✔️ Deep representation learning  

The combination of YOLOv8 + ResNet-18 improves both:

- Detection accuracy
- Crack localization capability

---

## 📊 4. Detection & Classification

The system:

- Detects crack regions
- Classifies cracked/non-cracked surfaces
- Extracts individual crack segments
- Saves highlighted crack outputs

---

## 🧠 5. Explainable AI with Grad-CAM

Grad-CAM visualization highlights the regions influencing predictions.

This improves:

✅ Transparency  
✅ Interpretability  
✅ Engineering trustworthiness  
✅ Validation support  

---

## 🖼️ 6. Final Visualization

The final output includes:

✔️ Bounding-box crack localization  
✔️ Crack-highlighted regions  
✔️ Individual crack segmentation  
✔️ Detection confidence visualization  

---

# 🖼️ System Demonstration

<p align="center">
  <img src="project_overview.png" width="1000"/>
</p>

---

# 📊 Model Performance

<div align="center">

| Metric | Score |
|---|---|
| Accuracy | 95.70% |
| Precision | 95.10% |
| Recall | 96.20% |
| F1-Score | 95.60% |
| AUC Score | 0.974 |

</div>

---

# 📌 Confusion Matrix Analysis

The confusion matrix demonstrates strong crack classification capability.

### Key Observations:

✔️ High True Positive Rate  
✔️ Strong Non-Crack Detection  
✔️ Low False Positives  
✔️ Balanced Classification Performance  

<p align="center">
  <img src="confusion_matrix.png" width="900"/>
</p>

---

# 📈 ROC Curve & AUC Analysis

The ROC Curve demonstrates excellent crack vs non-crack discrimination capability.

### Achievements:
- AUC Score: **0.974**
- High sensitivity & specificity balance
- Strong classification reliability

<p align="center">
  <img src="roc_curve_analysis.png" width="1000"/>
</p>

---

# 🧠 Explainable AI using Grad-CAM

Unlike traditional black-box systems, this project integrates **Grad-CAM Explainable AI** to visually interpret model decisions.

## 🔍 Benefits

✅ Highlights crack-affected regions  
✅ Improves AI transparency  
✅ Assists engineers during inspection  
✅ Enhances deployment trustworthiness  
✅ Supports interpretable infrastructure AI systems  

---

# 💼 Real-World Operational Impact

<div align="center">

| Operational Area | Improvement |
|---|---|
| Inspection Time | 25–30 Days → 3–5 Days |
| Workforce Requirement | 3–5 Inspectors → 1–2 Technicians |
| Operational Cost Reduction | ~72% |
| Estimated Savings | ~₹9 Lakhs per Site |
| Estimated ROI | ~270% |

</div>

---

# 📁 Dataset Information

## 📌 Dataset
Concrete Surface Crack Image Dataset

## 📌 Classes
- Crack
- No Crack

## 📌 Preprocessing Techniques
- Resizing
- Normalization
- Data Augmentation
- Noise Reduction

---

# 🛠️ Technology Stack

<div align="center">

| Category | Technologies |
|---|---|
| 💻 Programming | Python |
| 🧠 Deep Learning | PyTorch |
| 🎯 Object Detection | YOLOv8 |
| 👁️ Computer Vision | OpenCV |
| 🌐 Web Framework | Flask |
| 📊 Visualization | Matplotlib |
| 🔍 Explainability | Grad-CAM |

</div>

---

# 🧠 Concepts Used

- Deep Learning
- Computer Vision
- Object Detection
- Explainable AI
- CNN Architectures
- Transfer Learning
- Image Classification
- Infrastructure AI

---

# 📂 Project Structure

```bash
AI-Powered-Concrete-Crack-Detection/
│
├── dataset/
├── models/
├── crack_outputs/
├── static/
├── templates/
├── images/
│   ├── architecture_pipeline.png
│   ├── project_overview.png
│   ├── confusion_matrix.png
│   └── roc_curve_analysis.png
│
├── app.py
├── crack_detection.ipynb
├── model.pth
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Janicebenita/AI-Powered-Concrete-Crack-Detection-System-with-Explainable-AI-Grad-CAM-.git
```

---

## 2️⃣ Navigate to Project Directory

```bash
cd AI-Powered-Concrete-Crack-Detection-System-with-Explainable-AI-Grad-CAM-
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Run Application

```bash
python app.py
```

---

# 🌐 Open in Browser

```text
http://127.0.0.1:5000
```

---

# 🚀 Future Upgradation & Research Scope

This project can be further enhanced into a large-scale industrial infrastructure inspection platform.

## 🔮 Planned Enhancements

### 🚁 Drone-Based Crack Inspection
Integrate UAV/drone imaging for automated bridge and building inspection.

---

### 🎥 Real-Time Video Crack Detection
Enable live crack detection from video streams.

---

### 📱 Mobile & Edge AI Deployment
Deploy lightweight optimized models on:

- Mobile devices
- Raspberry Pi
- Edge AI systems

---

### ☁️ Cloud-Based Monitoring Dashboard
Develop centralized cloud infrastructure monitoring systems.

---

### 📊 Multi-Class Crack Severity Analysis
Extend system to classify:

- Minor cracks
- Moderate cracks
- Severe structural damage

---

### 🛰️ Smart City Infrastructure Integration
Future integration with:

- Smart surveillance systems
- IoT sensors
- Predictive maintenance platforms

---

# 📜 License & Acknowledgement

This project was developed for educational, research, and industry-oriented learning purposes under the guidance and support of:

<div align="center">

# 🏢 M/s Larsen & Toubro – Divisional Corporate

</div>

Special thanks to **M/s Larsen & Toubro – Divisional Corporate** for their technical guidance, domain expertise, and mentorship throughout the project development process.

---

## 📌 Usage Notice

This repository is intended for:

- Educational Purposes
- Research & Learning
- Portfolio Demonstration
- Non-commercial AI Exploration

Unauthorized commercial redistribution or misuse of project assets or proprietary insights is discouraged.

---

# ⭐ Project Highlights

✅ Hybrid YOLOv8 + ResNet-18 Pipeline  
✅ Explainable AI Integration  
✅ Real-world Infrastructure AI Application  
✅ Automated Crack Localization  
✅ Industry-Oriented Deep Learning Solution  
✅ Scalable Inspection Architecture  

---

# 👩‍💻 Author

<div align="center">

# Janice Benita F

### AI • Machine Learning • Computer Vision Enthusiast

🎓 B.Tech – Information Technology (2023–2027)

📧 janicebenita123@gmail.com

🔗 GitHub  
https://github.com/Janicebenita

🔗 LinkedIn  
https://linkedin.com/in/janice13

</div>

---

# 🤝 Contributions

Contributions, feedback, and suggestions are welcome!

## Steps:
1️⃣ Fork the repository  
2️⃣ Create a feature branch  
3️⃣ Commit your changes  
4️⃣ Push to GitHub  
5️⃣ Open a Pull Request  

---

# ⭐ Support This Project

If you found this project useful:

⭐ Star the repository  
🍴 Fork the project  
💡 Share your feedback  
🚀 Contribute improvements  

---

<div align="center">

# 🏗️ Building Smarter Infrastructure Inspection using AI

### Powered by YOLOv8, ResNet-18 & Explainable AI

⭐ Star This Repository If You Like The Project ⭐

</div>
