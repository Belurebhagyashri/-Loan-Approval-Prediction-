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
Loan_Approval_Prediction/
│── Loan_Approval_Prediction.ipynb
│── README.md
│── requirements.txt (optional)
│── images/ (optional: store charts/plots here)


---

## 📌 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/Loan_Approval_Prediction.git
   
2. Install dependencies:
   pip install -r requirements.txt

3.Run Jupyter Notebook:
      jupyter notebook Loan_Approval_Prediction.ipynb

      
---

