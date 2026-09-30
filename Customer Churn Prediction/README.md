# 👥 Project 3: Customer Churn Prediction System (Classification)

This repository contains the predictive classification pipeline built to identify customer retention patterns.

## 🚀 Project Objective
The objective is to build a binary classification model that accurately predicts whether a telecom customer is likely to cancel their service (churn) based on their account information, demographics, and contract usage details.

## 📁 Folder Contents
* `Customer Churn Prediction.ipynb` -> Step-by-step classification framework, model comparisons, and evaluations.
* `Telco-Customer-Churn.csv` -> Raw telecom customer profile data.

## 🛠️ Methodology & Steps
1. **Advanced Cleaning:** Handled structural object-to-numeric anomalies (such as whitespaces in the `TotalCharges` column).
2. **Feature Encoding:** Utilized One-Hot Encoding on categorical attributes to prep data for classification algorithms.
3. **Feature Selection:** Filtered out weak indicators to isolate account attributes most strongly correlated with customer churn.
4. **Model Comparison:** Evaluated multiple classification architectures side-by-side.

## 🤖 Models Tested
* **Random Forest Classifier**
* **Logistic Regression**
* **Decision Tree Classifier**

## 📊 Evaluation Framework
To ensure business value (balancing false positives vs. false negatives), the models were thoroughly vetted using:
* **Accuracy, Precision, Recall, and F1-Score**
* **Confusion Matrix Analysis**

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
