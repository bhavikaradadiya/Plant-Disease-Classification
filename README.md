# Plant-Disease-Classification
# 🌿 Advanced Image Classification for Automated Disease Diagnosis Using Computer Vision

This repository presents a deep learning–based computer vision project for **automated plant disease diagnosis** using **Convolutional Neural Networks (CNNs)** and **transfer learning** with **ResNet-50**.  
The work demonstrates how modern AI methods can be applied to improve **agricultural productivity**, **reduce manual diagnosis time**, and **enable early disease detection**.

---

## 🧑‍🎓 Project Details

**Title:** Advanced Image Classification for Automated Disease Diagnosis Using Computer Vision  
**Author:** Radadiya Bhavikaben Bavchandbhai  
**Programme:** MSc Data Analytics  
**Year:** 2025  
**Institution:** Berlin School of Business and Innovation 

---

## 🧠 Overview

Plant diseases often exhibit subtle visual symptoms that are difficult to detect manually.  
This project implements a **ResNet-50 CNN** using **TensorFlow/Keras** for classifying **Mango Leaf Diseases** into eight categories.  

The model leverages **transfer learning** from **ImageNet** to efficiently learn disease-specific features, even with a relatively small dataset.  
Through preprocessing, data augmentation, and fine-tuning, the model achieves strong generalization performance.

---

## 📂 Dataset

**Dataset Used:** [Mango Leaf Disease Dataset (Kaggle)](https://www.kaggle.com/datasets/aryashah2k/mango-leaf-disease-dataset)  

**Classes (8 Total):**
1. Anthracnose  
2. Bacterial Canker  
3. Cutting Weevil  
4. Die Back  
5. Gall Midge  
6. Healthy  
7. Powdery Mildew  
8. Sooty Mould  

**Dataset Size:** 4,000 images (500 per class)  
**Split:** 80% Training | 20% Validation  

---

## ⚙️ Data Preprocessing

Preprocessing steps applied before training:

- **Resizing:** All images resized to `224x224` pixels.  
- **Normalization:** Pixel values scaled to `[0, 1]`.  
- **Data Augmentation:** Random rotation, flipping, zooming, and brightness changes to enhance variability.  
- **Label Encoding:** Class labels derived automatically from folder names.  

---

## 🧩 Model Architecture

**Model:** ResNet-50 (Pretrained on ImageNet)  
**Framework:** TensorFlow / Keras  
**Optimizer:** RMSprop (learning rate = 0.0001)  
**Loss Function:** Categorical Crossentropy  
**Metrics:** Accuracy  

**Architecture Highlights:**
- Residual blocks to solve vanishing gradient problem.  
- Transfer learning for efficient training on limited data.  
- Fully connected dense layer (Softmax activation) for 8-class output.  
- Dropout layer to prevent overfitting.  

---

## 🚀 Training and Evaluation

**Training Configuration:**
- Epochs: 10  
- Batch Size: 32  
- Validation Split: 20%  
- Early stopping and checkpointing used for best performance.  

**Model Performance (Example Results):**
| Metric | Training | Validation |
|:-------|:----------|:-----------|
| Accuracy | 96.4% | 92.1% |
| Precision | 0.93 | 0.91 |
| Recall | 0.92 | 0.90 |
| F1 Score | 0.91 | 0.90 |

---

## 📊 Visualizations

Visualizations generated during model evaluation:

- 📈 **Accuracy and Loss Curves**
- 📉 **Confusion Matrix**
- 🌱 **Sample Predictions** (actual vs predicted)
- 🔍 **Feature Maps / Activation Layers** (optional visualization)

All plots and results are available under the `/outputs/plots/` directory.

---

## 🧮 Installation and Usage

### 1️ Clone Repository
```bash
git clone https://github.com/yourusername/Plant-Disease-Classification.git
cd Plant-Disease-Classification
```

### 2️ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3  Open in Google Colab
Upload the notebooks in `/notebooks/` and run each cell sequentially.

---

## 📘 Requirements

- Python 3.10+
- TensorFlow 2.16+
- Keras 3+
- OpenCV 4+
- Matplotlib, Seaborn, NumPy, Pandas, Pillow

All dependencies listed in `requirements.txt`.

---

## 🧾 References

- He, K., Zhang, X., Ren, S., & Sun, J. (2016). *Deep Residual Learning for Image Recognition.* CVPR.  
- Ferentinos, K.P. (2018). *Deep Learning Models for Plant Disease Detection.* Computers and Electronics in Agriculture.  
- Shorten, C. & Khoshgoftaar, T.M. (2019). *A Survey on Image Data Augmentation for Deep Learning.*  
- Paszke, A. et al. (2019). *PyTorch: An Imperative Style, High-Performance Deep Learning Library.*  
- Abadi, M. et al. (2016). *TensorFlow: Large-Scale Machine Learning on Heterogeneous Systems.*

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 🏁 Acknowledgements
Special thanks to **Kaggle** for dataset hosting and **TensorFlow/Keras** community for open-source deep learning resources.  
This work was completed as part of the MSc coursework in Computer Vision & AI, demonstrating practical applications of transfer learning in agriculture.


