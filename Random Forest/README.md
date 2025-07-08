# 🌲 Random Forest Classifier on Iris Dataset

This project demonstrates the use of a **Random Forest Classifier** with hyperparameter tuning via `GridSearchCV` to classify the famous Iris dataset.

---

## 📁 Dataset
- **Source**: `sklearn.datasets.load_iris()`
- **Classes**: Setosa, Versicolor, Virginica
- **Features**: Sepal Length, Sepal Width, Petal Length, Petal Width

---

## 🚀 Workflow

1. Load the Iris dataset.
2. Preprocess the data (train-test split).
3. Define a parameter grid for tuning:
   - `n_estimators`: Number of trees
   - `max_depth`: Maximum tree depth
   - `min_samples_split`: Minimum samples to split a node
4. Use `GridSearchCV` for hyperparameter tuning.
5. Train and evaluate the model.
6. Report best parameters and test accuracy.

---

## 📊 Output
- Best Hyperparameters via GridSearchCV
- Cross-validation accuracy
- Final test accuracy using the best model

---

## 🧰 Requirements

Install all dependencies with:
```bash
pip install -r requirements.txt
