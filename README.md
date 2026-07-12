# 🌹 Taif Rose Image Classification System

An end-to-end computer vision project developed to classify the authentic Taif Rose against the commercial Damask Rose using deep learning.

---

## 🎯 Project Inspiration
Taif city is globally renowned as the **"City of Roses"**, cultivating over 900 million roses annually. The unique high-altitude climate of **Taif, Saudi Arabia**, infuses its local rose with a distinct molecular identity and look. This project leverages Artificial Intelligence to preserve and identify our city's floral heritage against the standard Damask variant.

---

## 🛠️ Tech Stack & Frameworks
* **Language:** Python
* **Environment:** Google Colab / Jupyter Notebook
* **Deep Learning Framework:** Keras & TensorFlow
* **Computer Vision Library:** Pillow (PIL) & NumPy
* **Core Architecture:** MobileNet / Convolutional Neural Networks (CNN)

---

## ⚡ Quick Steps
<kbd>Step 1</kbd> **Dataset Preparation:** Collected and cropped high-resolution images to a uniform square size of $224 \times 224$ pixels.
<kbd>Step 2</kbd> **Model Training:** Employed Transfer Learning via Teachable Machine using a pre-trained CNN.
<kbd>Step 3</kbd> **Deployment & Inference:** Exported the `.h5` model weights and implemented a Python script for testing.

---

## 📸 Training Dataset Sample

### Class 1: Taif Rose (Light pink, delicate, multi-layered petals)
<img src="https://picsum.photos/id/669/100/100" width="100" height="100"/> <img src="https://picsum.photos/id/669/100/100" width="100" height="100"/> <img src="https://picsum.photos/id/669/100/100" width="100" height="100"/>

### Class 2: Damask Rose (Deep red, structured, spiral petals)
<img src="https://picsum.photos/id/152/100/100" width="100" height="100"/> <img src="https://picsum.photos/id/152/100/100" width="100" height="100"/> <img src="https://picsum.photos/id/152/100/100" width="100" height="100"/>

> 💡 *Note: All training images were automatically normalized and resized to $224 \times 224$ pixels before the matrix training stage.*

---

## 🏆 Final Evaluation & Results

| Metric | Classification Performance | Status |
| :--- | :---: | :---: |
| **Model Type** | Keras Deep Learning (`.h5`) | Fully Trained |
| **Input Shape** | $224 \times 224 \times 3$ (RGB) | Verified |
| **Prediction Output** | Class Name & Confidence Score | Active |

### 🚀 Try It Live
Click the badge below to run and test the interactive code directly inside your browser:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](ضعي_رابط_مشاركة_كولاب_الأزرق_هنا)
