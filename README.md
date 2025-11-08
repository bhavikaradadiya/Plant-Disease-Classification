# 🌿 Advanced Image Classification for Automated Plant Disease Diagnosis Using CNN

This repository contains the implementation of a **Custom Convolutional Neural Network (CNN)** model that classifies plant leaf images into 38 disease or healthy categories using the **PlantVillage dataset**.  
The project is implemented entirely in a single Python file — `plant_disease_detection.py`.

---

## 🚀 Project Summary
Traditional disease detection in plants is labor-intensive and relies on expert knowledge.  
This project uses **deep learning and computer vision** to automate plant disease diagnosis from leaf images — improving accuracy and enabling early intervention.

---

## 📊 Dataset
- **Dataset:** [PlantVillage Dataset](https://www.kaggle.com/datasets/mohitsingh1804/plantvillage)
- **Total Images:** 54,305
- **Classes:** 38 (healthy + diseased)
- **Split:** 80% training / 20% testing

---

## 🧠 Model Overview
The project uses a **Custom CNN architecture** built using TensorFlow and Keras APIs.  
**Key layers include:**
- Convolutional (Conv2D) layers
- MaxPooling2D layers
- Dropout layers (to prevent overfitting)
- Dense layers for classification
- Softmax activation for 38 categories

---

## ⚙️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Plant-Disease-Classification.git
   cd plant-disease-detection-cnn
