<h1 align="center">🩺 Mammographic Masses Analysis using Decision Tree</h1>

<p align="center">
  This project applies a Decision Tree Classifier to analyze and predict the severity of mammographic masses based on medical features such as age, shape, density, and margin.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numpy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
</p>

---

## 🧠 Project Overview

This project uses a **Decision Tree Classifier** to predict whether a detected mammographic mass is **benign (0)** or **malignant (1)** based on input features. The model is trained using a clean dataset and evaluated using accuracy and confusion matrix. The goal is to assist early-stage detection of breast cancer using basic diagnostic data.

---

## 📊 Dataset Information

The dataset contains the following columns:

| Feature         | Description                                      |
|-----------------|--------------------------------------------------|
| `BI-RADS`           | A score (1–5) indicating the level of concern from the mammogram result                               |
| `Age`           | Age of the patient                               |
| `Shape`         | Shape of the mass (1: round, 2: oval, 3: lobular, 4: irregular) |
| `Margin`        | Margin of the mass (1–5 coded scale)             |
| `Density`       | Density of the mass (1: high, 2: iso, 3: low, 4: fat-containing) |
| `Target`      | Target label – 0: benign, 1: malignant            |

---

## 🚀 WorkFlow

1. Load the dataset and handle missing values (if any)
2. Visualize the data using histograms and count plots
3. Split the dataset into training and testing sets
4. Train a Decision Tree Classifier using `scikit-learn`
5. Predict on test set and evaluate using accuracy
6. Visualize the confusion matrix
