# 🧠 Principal Component Analysis (PCA) on Breast Cancer Dataset

This repository contains a clean and well-documented Jupyter Notebook demonstrating **Principal Component Analysis (PCA)** using the Breast Cancer dataset from `sklearn.datasets`.

## 📌 Objective
To reduce the dimensionality of the dataset from 30 features to 2 principal components for visualization and to understand the structure of the data.

## 📁 Files
- `PCA_Insights_Ready.ipynb`: Jupyter Notebook with step-by-step PCA implementation, insights, and plots.
- `README.md`: This file.

## 🔍 Dataset Overview
- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Samples**: 569
- **Features**: 30 numeric measurements of cell nuclei
- **Target**: Binary classification — Malignant (0) or Benign (1)

## 📈 Key Steps in the Notebook
1. **Loading the dataset**
2. **Standardizing the features**
3. **Applying PCA** to reduce to 2 components
4. **Explained Variance Ratio** visualization
5. **2D scatter plot** of principal components
6. **Interpretation** of variance and class separability

## 📊 Visualization
PCA scatter plots and variance bar charts are included to demonstrate how much information is retained in the 2 principal components.

## 🧠 Insights
- PCA effectively captures the structure of the dataset.
- The first two components retain a significant portion of the variance.
- Malignant and Benign samples show some separation in PCA space.

## 🚀 How to Run
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
jupyter notebook PCA_Insights_Ready.ipynb
