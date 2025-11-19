# TASK04--TELCOM-CHURN-PRDICTION
📌 Project Overview

This project predicts whether a telecom customer will churn (leave the company) using machine learning.
Dataset used: WA_Fn-UseC_-Telco-Customer-Churn (1).csv

🛠 Tools & Libraries

Python

Pandas

NumPy

Matplotlib / Seaborn

scikit-learn

joblib (for saving model)

🔄 Steps Performed
1️⃣ Load the Dataset

Read the CSV file

Clean missing values

Convert “TotalCharges” to numeric

2️⃣ Preprocessing

Label Encoding for Yes/No columns

One-Hot Encoding for multi-class columns

Train-Test Split

Standard Scaling for numeric features

3️⃣ Model Building

Used RandomForestClassifier

Checked accuracy

Displayed feature importance

4️⃣ Save the Model

Saved using joblib:

import joblib
joblib.dump(model, "churn_model.pkl")

📂 Files in Project

notebook.ipynb – full code

churn_model.pkl – trained model

README.md – project explanation

dataset.csv – Telco churn dataset

🎯 Output

Predicts Churn: Yes/No for each customer.
