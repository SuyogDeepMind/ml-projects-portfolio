# 📊 Linear Regression on Advertising Dataset

This project demonstrates the use of Linear Regression to predict **sales revenue** based on advertising spending across various media channels such as TV, Radio, and Newspaper.

## 📁 Dataset
The dataset used is the **Advertising dataset**, which contains:
- TV, Radio, and Newspaper advertising budgets
- Corresponding sales outcomes

## 🚀 Project Workflow

1. **Exploratory Data Analysis (EDA)**:
   - Visualized relationships between features and target variable
   - Checked correlation heatmaps

2. **Model Training**:
   - Applied Linear Regression using `scikit-learn`
   - Split the data into training and test sets

3. **Evaluation Metrics**:
   - R² Score
   - Mean Squared Error (MSE)
   - Residual plots

## 📈 Results
The model showed a strong linear relationship, especially between TV advertising and sales, with a high R² value indicating good predictive power.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn

## 💡 Key Learnings
- Understanding of simple linear regression
- Visual analysis to identify feature impact
- How to evaluate regression models using real-world data

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook Linear_Regression.ipynb
```
