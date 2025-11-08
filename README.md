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
2. Install dependencies:
   
   pip install -r requirements.txt

3. Run the project:

   Custom_CNN.ipynb

##  🧩 Main File — Custom_CNN.ipynb

This single script contains:

1. Dataset extraction and loading

2. Data preprocessing and augmentation

3. CNN model creation (Custom CNN)

4. Model training and validation

5. Evaluation metrics — Accuracy, Precision, Recall, F1-score

6. Visualization of accuracy/loss curves


## 🧾 References

He, K. et al. (2016). Deep Residual Learning for Image Recognition.

LeCun, Y. et al. (1998). Gradient-based Learning Applied to Document Recognition.

Shorten, C. & Khoshgoftaar, T. (2019). Image Data Augmentation for Deep Learning.

## 👩‍💻 Author

Bhavika Bavchandbhai Radadiya
Computer Vision and Artificial Intelligence (2025)


   
