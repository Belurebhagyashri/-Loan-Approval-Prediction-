# 💳 Loan Approval Prediction 🔮

Smarter Banking with Machine Learning & Explainable AI (SHAP)

#🌟 Project Overview

This project predicts whether a loan application should be approved or rejected using machine learning.
It helps financial institutions reduce risk and speed up decision-making by learning from past loan applicant data.

#📌 Objective

Build ML models that predict loan approval status based on applicant details (income, credit history, dependents, loan amount, etc.).

Compare different algorithms and choose the most accurate and interpretable model.

#📂 Dataset Information

Size: 1500+ records

Features: 10 numerical + 8 categorical

Target: Loan approval status (Approved / Not Approved)

#🛠️ Workflow

Data Collection → Import dataset (Excel/CSV)

EDA (Exploratory Data Analysis) → Visualize distributions, correlations

Data Preprocessing

Handle missing values

Encode categorical variables (One-hot encoding, Label encoding)

Normalize/scale numerical features

Model Training → Logistic Regression, SVM, Decision Tree

Model Evaluation → Accuracy, Precision, Recall, F1-score, Confusion Matrix

Explainability with SHAP → Feature importance & interpretation

#🤖 Models Used & Accuracy

Logistic Regression → ✅ Best (79.03%)

Support Vector Machine (SVM) → 69.35%

Decision Tree → 66.13%

#📊 Key Insights

Credit History is the most important predictor.

Logistic Regression balances simplicity and performance best.

SHAP values explain which features influenced the model’s predictions.

#⚙️ Tech Stack

Language: Python 🐍

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, shap

Environment: Jupyter Notebook
#🚀 How to Run the Project
# #Clone this repository
git clone https://github.com/your-username/loan-approval-prediction.git

## Navigate to folder
cd loan-approval-prediction

## Install dependencies
pip install -r requirements.txt

## Run Jupyter Notebook
jupyter notebook Loan_Approval_Prediction.ipynb

#🏆 Conclusion

Logistic Regression gave the best performance for this dataset.

SHAP helped improve model transparency by showing which features matter most.

This project can be extended to include more data and advanced models (XGBoost, Random Forest).

# 🏦 Loan Approval Prediction

## 📌 Project Overview
This project predicts whether a loan application will be **approved** or **rejected** based on applicant details.  
The goal is to help banks and financial institutions make better, data-driven decisions while minimizing risks.

---

## 📊 Dataset
The dataset includes information such as:
- Applicant Income
- Coapplicant Income
- Loan Amount & Term
- Credit History
- Gender, Marital Status, Education, Employment
- **Target Variable**: Loan Status (Y = Approved, N = Rejected)

---

## 🔧 Steps in the Project
1. **Data Cleaning & Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Normalize numerical values

2. **Exploratory Data Analysis (EDA)**
   - Visualizations of loan approval trends
   - Key insights (credit history, income, etc.)

3. **Model Building**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost

4. **Model Evaluation**
   - Accuracy, Precision, Recall, ROC-AUC
   - Confusion Matrix

5. **Model Explainability (SHAP)**
   - Feature importance using SHAP values
   - Explain why a loan is approved or rejected

---

## 📈 Results
- Best model: **Random Forest** (update based on your notebook)
- Accuracy: **82%**
- Most important features: **Credit History, Applicant Income, Loan Amount**

---

## 🚀 Deployment (Optional)
This model can be deployed using:
- **Streamlit / Flask** for a web interface
- Users can enter their loan details and instantly see predictions

---

## 🖼️ Sample Visualizations
*(Add images of your plots, e.g., SHAP summary, bar plots)*

---

## 📂 Project Structure
