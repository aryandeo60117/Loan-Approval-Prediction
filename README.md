# Loan-Approval-Prediction
Loan Default Prediction using XGBoost | Machine Learning | Feature Engineering | Model Evaluation | Python | Scikit-learn
# 💳 Loan Default Prediction using XGBoost

A machine learning project that predicts whether a loan applicant is likely to default based on their financial profile, credit history, employment details, and loan characteristics. This project leverages the powerful **XGBoost Classifier** to achieve high prediction performance while providing insights into the key factors influencing loan default.

---

## 📌 Project Overview

Financial institutions face significant risks when approving loans. Accurately predicting whether an applicant is likely to default helps reduce financial losses and improve lending decisions.

This project develops a supervised machine learning model using **XGBoost** to classify loan applications as either:

- **0 → No Default**
- **1 → Default**

The model is trained on historical loan application data and evaluated using multiple classification metrics.

---

## 🚀 Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Categorical Feature Encoding
- Missing Value Handling
- XGBoost Classifier
- Model Evaluation
- Confusion Matrix
- ROC-AUC Score
- Feature Importance Visualization
- Prediction on New Loan Applications

---

## 📂 Dataset Features

| Feature | Description |
|----------|-------------|
| id | Unique Loan Identifier |
| person_age | Applicant Age |
| person_income | Annual Income |
| person_home_ownership | Home Ownership Status |
| person_emp_length | Employment Length |
| loan_intent | Purpose of Loan |
| loan_grade | Credit Grade |
| loan_amnt | Loan Amount |
| loan_int_rate | Interest Rate |
| loan_percent_income | Loan Amount as Percentage of Income |
| cb_person_default_on_file | Previous Default History |
| cb_person_cred_hist_length | Credit History Length |
| loan_status | Target Variable |

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

---

## 📊 Machine Learning Pipeline

```
Data Collection
       │
       ▼
Data Cleaning
       │
       ▼
Exploratory Data Analysis
       │
       ▼
Feature Engineering
       │
       ▼
Categorical Encoding
       │
       ▼
Train-Test Split
       │
       ▼
XGBoost Classifier
       │
       ▼
Model Evaluation
       │
       ▼
Prediction
```

---

## 📈 Model Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

Example:

```
Accuracy : XX%
Precision: XX%
Recall   : XX%
F1 Score : XX%
ROC-AUC  : XX%
```

*(Replace with your actual scores.)*

---

## 📊 Feature Importance

The model identifies the most influential features affecting loan default prediction, including:

- Loan Grade
- Loan Interest Rate
- Loan Percent Income
- Annual Income
- Previous Loan Default
- Loan Amount
- Credit History Length

---

## 📁 Project Structure

```
Loan-Default-Prediction/
│
├── data/
│   ├── loan_data.csv
│
├── notebooks/
│   └── Loan_Default_Prediction.ipynb
│
├── models/
│   └── xgboost_model.pkl
│
├── images/
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│
├── requirements.txt
├── README.md
└── app.py
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Loan-Default-Prediction.git
```

Navigate to the project directory

```bash
cd Loan-Default-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook or application

```bash
jupyter notebook
```

or

```bash
python app.py
```

---

## 📷 Sample Output

- Loan Default Prediction
- Probability Score
- Feature Importance Plot
- Confusion Matrix
- Model Performance Metrics

---

## 🎯 Future Improvements

- Hyperparameter Optimization using Optuna
- SHAP Explainability
- Streamlit Web Application
- Model Deployment
- REST API Integration
- Real-Time Prediction Dashboard

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data Preprocessing
- Feature Engineering
- Classification Models
- XGBoost
- Model Evaluation
- Machine Learning Workflow
- Data Visualization

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork this repository and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Aryan Deo**

B.Tech Computer Science Engineering

Machine Learning & AI Enthusiast

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile
