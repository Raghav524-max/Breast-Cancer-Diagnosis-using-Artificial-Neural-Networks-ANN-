# Breast-Cancer-Diagnosis-using-Artificial-Neural-Networks-ANN-
# 🎗️ Breast Cancer Classification using ANN

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Deep Learning](https://img.shields.io/badge/Model-ANN-red)

## 📌 Overview
This project utilizes an **Artificial Neural Network (ANN)** to classify breast cancer tumors as Malignant or Benign. By leveraging deep learning, the model identifies patterns in clinical features to provide high-accuracy diagnostic support.

## 📊 Dataset
The project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset**.
- **Features:** 30 (Radius, Texture, Smoothness, etc.)
- **Target:** Diagnosis (Malignant/Benign)

## 🛠️ Workflow

### 1. Exploratory Data Analysis (EDA)
- **Statistical Analysis:** Visualized feature distributions and skewness.
- **Correlation Mapping:** Used Seaborn heatmaps to identify relationships between clinical parameters.

### 2. Feature Engineering
- **Standardization:** Applied scaling to normalize feature magnitudes.
- **Label Encoding:** Converted target labels for neural network compatibility.

### 3. ANN Architecture
- **Input Layer:** 30 neurons (one for each feature).
- **Hidden Layers:** Deep layers with ReLU activation for non-linear pattern recognition.
- **Output Layer:** Sigmoid activation for binary classification.

## 📈 Results
The model performance is evaluated using a **Confusion Matrix** to ensure diagnostic reliability.

| Metric | Value |
| :--- | :--- |
| **Accuracy** | 98% (Approx) |

## ⚙️ Tech Stack
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, TensorFlow/Keras

