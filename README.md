# 🧠 Brain Tumor Detection System using CNN

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/TensorFlow-2.14-orange?style=for-the-badge&logo=tensorflow" />
  <img src="https://img.shields.io/badge/OpenCV-4.x-green?style=for-the-badge&logo=opencv" />
  <img src="https://img.shields.io/badge/Google_Colab-yellow?style=for-the-badge&logo=googlecolab" />
</div>

---

## 📝 Project Overview

The **Brain Tumor Detection System** leverages deep learning (CNN) to automatically detect the presence and type of brain tumors from MRI images. It supports classification of:

- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor**

This system aims to assist radiologists and doctors in early and accurate tumor diagnosis using artificial intelligence.

---

## 🧠 Technologies Used

| Tool | Purpose |
|------|---------|
| 🐍 Python | Core programming language |
| 📦 TensorFlow / Keras | Deep learning model development |
| 🖼️ OpenCV | Image processing and visualization |
| 📁 Google Colab | Training and evaluation |
| 📊 Matplotlib | Graphical visualization of training progress |

---

## 📁 Dataset

The dataset used is from the **Kaggle Brain Tumor Classification Challenge** and contains MRI images classified into four categories.

> [📎 Dataset Source](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

---

## 🚀 How It Works

1. **Data Preprocessing**  
   - Load images from four classes  
   - Resize and normalize input data  
   - Label encode tumor types

2. **Model Architecture**  
   - CNN with Conv2D, MaxPooling, Dropout, and Dense layers  
   - Trained on 80% of the data, validated on 20%

3. **Evaluation**  
   - Accuracy, confusion matrix, and classification report  
   - Visualization of loss/accuracy graphs

4. **Prediction**  
   - Upload an image  
   - Model outputs tumor type (or "No Tumor")

---

## 📈 Results

- **Training Accuracy:** ~98%  
- **Validation Accuracy:** ~96%  
- **Loss convergence:** Stable with low overfitting

---

## 🛠️ Installation

To run locally:

```bash
git clone https://github.com/Veeraj71/Brain_Tumor_Detection_System.git
cd Brain_Tumor_Detection_System
pip install -r requirements.txt
