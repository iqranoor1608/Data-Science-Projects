# 📈 Sales Forecasting System (Regression)

This repository contains the end-to-end Machine Learning pipeline developed during Phase 1 of the Data Science Internship at **Sqrock IT Solution** to predict future sales and revenue trends using historical business data.

## 🚀 Project Objective
The goal of this project is to build an accurate predictive model that forecasts future business sales. Accurate forecasting helps businesses optimize inventory management, plan marketing budgets, and anticipate revenue fluctuations.

## 📁 Folder Contents
* `Data Science Internship Task 1.ipynb` -> Jupyter Notebook detailing EDA, preprocessing, and modeling.
* `train.csv` -> Historical sales dataset used for training and validation.

## 🛠️ Methodology & Steps
1. **Data Cleaning:** Addressed missing data, parsed date strings, and structured the time-series elements.
2. **Feature Engineering:** Implemented data slicing and formatting to prepare features for regression.
3. **Train-Test Splitting:** Segmented the historical data carefully to test the model's forecasting capability on unseen data.
4. **Model Training:** Deployed a robust **Random Forest Regressor** to capture non-linear relationships in the business data.

## 📊 Evaluation Metrics
The system evaluates the sales prediction variance and errors using:
* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
*
