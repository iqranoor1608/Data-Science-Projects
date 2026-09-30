# 🎓 Project 2: Student Performance Predictor (Regression)

This repository contains the predictive modeling workflow developed to analyze and estimate student academic success.

## 🚀 Project Objective
The objective is to predict a student's final academic performance (measured by GPA) by evaluating an array of features including study habits, lifestyle choices, and demographic variables.

## 📁 Folder Contents
* `Student Performance Predictor.ipynb` -> Comprehensive notebook containing demographic analysis and model tuning.
* `student-data.csv` -> Student profile dataset containing behavioral and academic metrics.

## 🛠️ Methodology & Steps
1. **Exploratory Data Analysis (EDA):** Leveraged data visualization tools to map correlations between study time, lifestyle choices, and final GPA.
2. **Data Preprocessing:** Encoded categorical features (e.g., demographics) into machine-readable numeric formats.
3. **Regression Modeling:** Evaluated various regression algorithms, prioritizing tree-based ensembles.
4. **Fine-Tuning:** Optimized the Regressor to ensure generalization and prevent overfitting.

## 🏆 Key Results
* **Primary Model:** Random Forest Regressor
* **Performance Metric:** Reached an outstanding **\(R^2\) Score of ~0.9356**, indicating that over 93.5% of the variance in student GPAs is successfully explained by the model features.

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
