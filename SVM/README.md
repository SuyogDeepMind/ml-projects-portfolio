# 🧠 Loan Approval Prediction using Support Vector Machine (SVM)

This project uses a Support Vector Machine (SVM) model to predict loan approval status based on customer details. The workflow includes data preprocessing, encoding, scaling, model training, and hyperparameter tuning using GridSearchCV.

---

## 📁 Dataset
- **Filename**: `loan_approved.csv`
- **Target column**: `Loan_Status (Approved)` (renamed to `Loan_Status`)
- **Features**: Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area

---

## 📌 Project Workflow
1. Importing libraries
2. Loading and preprocessing dataset
3. Encoding categorical variables
4. Handling missing values
5. Feature-target split
6. Feature scaling
7. Train-test split
8. Model training using SVM
9. Hyperparameter tuning using `GridSearchCV`
10. Model evaluation

---

## 🛠️ Requirements

Install dependencies using:
```bash
pip install -r requirements.txt
