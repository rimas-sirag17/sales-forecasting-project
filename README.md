#  Sales Forecasting using Machine Learning

##  Project Overview

This project aims to forecast future sales using historical data and machine learning regression models.  
We apply time-series feature engineering techniques such as lag features and rolling averages to improve prediction accuracy.

---

##  Objectives

- Analyze historical sales data
- Create time-based features (year, month, week, day)
- Generate lag and rolling features
- Train regression models
- Compare model performance
- Visualize actual vs predicted sales

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

##  Dataset

Dataset used: Walmart Sales Forecast (Kaggle)

Main columns:
- Date
- Weekly_Sales

---

##  Feature Engineering

The following features were created:

- Year
- Month
- Week
- Day
- Lag_1, Lag_2, Lag_4
- Rolling Mean (4 weeks)
- Rolling Standard Deviation (4 weeks)

---

##  Models Used

1. Linear Regression
2. Random Forest Regressor

---

##  Evaluation Metrics

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

---

##  Results

Random Forest performed better than Linear Regression in capturing time-based sales patterns.

---

##  Key Learnings

- Importance of time-aware data splitting
- Impact of lag features in forecasting
- Comparing regression models for time-series data

---

##  Future Improvements

- Implement XGBoost
- Use TimeSeriesSplit for cross-validation
- Add seasonal decomposition
- Deploy as Streamlit dashboard



**Rimas Serag Eldin Salah**  
Machine Learning Trainee  
