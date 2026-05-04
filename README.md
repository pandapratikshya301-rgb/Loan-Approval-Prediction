# 🏦 Loan Approval Prediction

This project builds a machine learning model to predict whether a loan application should be approved based on applicant details such as income, credit history, and loan amount.

---

## 📌 Problem Statement
Loan approval is a critical decision for financial institutions. Incorrect approvals can lead to financial loss, while incorrect rejections can reduce customer satisfaction.

This project aims to automate and improve this decision-making process using machine learning.

---

## 📊 Dataset
- Source: https://www.kaggle.com/datasets/bhanupratapbiswas/loan-approval-prediction-case-study
- Features include:
  - Applicant Income
  - Loan Amount
  - Credit History
  - Gender, Education, Employment status

---

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🔄 Workflow
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Handling Class Imbalance (SMOTE)
5. Model Training
6. Model Evaluation

---

## 🤖 Models Used
- Logistic Regression
- Decision Tree
- Random Forest

---

## 📈 Evaluation Metrics
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## 🧠 Key Insights
- Credit history is the strongest predictor
- Income significantly influences loan approval
- Loan-to-income ratio plays a major role

---

## 🚀 Results
Random Forest performed best among all models due to its ability to handle non-linear relationships and feature interactions.

---

## ⚠️ Business Considerations
- Lower threshold → more approvals but higher risk
- Higher threshold → safer decisions but fewer approvals

---

## 📁 Project Structure
Loan-Approval-Prediction/
│
├── Loan_Approval_Prediction.ipynb
├── README.md
└── images/

---

## 📌 Future Improvements
- Hyperparameter tuning
- Deployment using Flask/FastAPI
- Real-time prediction system

---

## 🔗 Author
[Pratikshya Panda]
