# K-Nearest Neighbors (KNN) - Classification & Regression

This project includes both classification and regression implementations of the **K-Nearest Neighbors (KNN)** algorithm using real-world datasets.

---

## ✅ Classification

**Dataset:** `diabetes.csv`  
**Objective:** Predict whether a person has diabetes based on diagnostic features.

**Notebook:** `KNN_Classification.ipynb`

---

## ✅ Regression

**Dataset:** `Housing.csv`  
**Objective:** Predict house prices based on various features using KNN.

**Notebook:** `KNN_Regression.ipynb`

---

## 📚 Theory Recap

### 📌 KNN Basics:
- Lazy learner algorithm
- Non-parametric, instance-based learning
- Classifies a new instance based on a majority vote or average of k-nearest neighbors

### 📌 Distance Metric:
- Euclidean Distance (most commonly used):  
\\[
\\text{Distance}(p, q) = \\sqrt{\\sum (p_i - q_i)^2}
\\]

### 📌 Classification:
- Majority voting of neighbors

### 📌 Regression:
- Mean of nearest neighbors' target values

---

## 🧠 Parameters:
- `n_neighbors`: Number of nearest neighbors to use
- `weights`: Uniform or distance
- `metric`: Distance measure (default: 'minkowski')

---

## 📦 Requirements

```bash
pip install -r requirements.txt
