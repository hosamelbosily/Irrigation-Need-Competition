
---

# 🌱 Irrigation Need Prediction (Deep Learning)

## 📌 Overview

This project was developed as part of the **Kaggle Irrigation Need Competition**.
It uses **Deep Learning (Artificial Neural Networks)** to predict the irrigation requirement level of crops based on environmental and soil conditions.

The main goal is to support **smart agriculture and water optimization** by predicting irrigation needs more accurately.

---

## 🎯 Problem Statement

Predict the irrigation requirement level:

* Low 💧
* Medium 💧💧
* High 💧💧💧

Based on environmental and agricultural features.

---

## 📊 Dataset

The dataset is taken from Kaggle:

🔗 [https://www.kaggle.com/datasets/miadul/irrigation-water-requirement-prediction-dataset](https://www.kaggle.com/datasets/miadul/irrigation-water-requirement-prediction-dataset)

### Features:

* 🌡️ Temperature
* 🌧️ Rainfall
* 🌱 Crop Type
* 🧱 Soil Type
* 💦 Evapotranspiration
* 🌿 Soil Moisture

### Target:

* `Irrigation_Need`

---

## 🧠 Model (Deep Learning)

A Neural Network (ANN) was used for classification.

### Architecture:

* Input Layer
* Multiple Dense Hidden Layers (ReLU)
* Dropout Layers (regularization)
* Output Layer (Softmax)

---

## ⚙️ Tech Stack

* Python 🐍
* TensorFlow / Keras 🤖
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn

---

## 🔄 Workflow

1. Data Cleaning
2. Encoding categorical features
3. Feature scaling
4. Train/Test split
5. Deep Learning model training
6. Evaluation (Accuracy / F1-score)

---

## 🏆 Results

* Good classification performance on validation data
* Deep Learning model improved feature learning compared to traditional ML models
* Stable training and generalization

---

## 📁 Repository Structure

```bash
Irrigation-Need-Competition/
│
├── data/               # Dataset files
├── notebooks/          # Jupyter notebooks
├── models/             # Saved model
├── src/                # Source code
├── README.md
└── requirements.txt
```

---
