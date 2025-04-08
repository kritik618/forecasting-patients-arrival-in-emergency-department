# Forecasting Patient Arrivals in Emergency Department

## 🩺 Overview
This project focuses on forecasting the number of daily patient arrivals in an Emergency Department (ED) by triage severity levels (ES1 to ES5), followed by a combined daily arrival forecast. Accurate forecasting enables better staffing, improved patient flow, and effective resource allocation.

We used multiple machine learning and statistical models including:
- Multiple Linear Regression
- Support Vector Machine (SVM)
- ARIMA
- SARIMA
- Holt-Winters Exponential Smoothing

---

## 📁 Project Structure

notebooks/ ├── ES1_forecasting.ipynb # Forecasting arrivals for Emergency Severity Level 1 ├── ES2_forecasting.ipynb # Forecasting arrivals for ES2 ├── ES3_forecasting.ipynb # Forecasting arrivals for ES3 ├── ES4_forecasting.ipynb # Forecasting arrivals for ES4 ├── ES5_forecasting.ipynb # Forecasting arrivals for ES5 └── total_combined_forecast.ipynb # Daily forecasting by combining ES1 to ES5
Each notebook contains:
- Data preprocessing
- Feature engineering
- Model building
- Forecasting
- Evaluation using RMSE, MAPE, and visual plots

---

## 📊 Dataset Description

> ⚠️ **Note:** The dataset is not uploaded in this repository due to privacy or size constraints.

The dataset contains historical records of patient arrivals across 5 severity levels:
- `date`: Date of arrival
- `ES1` to `ES5`: Count of arrivals per severity level per day
- `total_arrivals`: Sum of ES1–ES5 per day
- `is_holiday`, `day_of_week`: Additional features for modeling
  
## 📈 Techniques Used
- Time Series Decomposition
- Seasonal ARIMA (SARIMA)
- Holt-Winters Exponential Smoothing
- Support Vector Regression (SVR)
- Model comparison using MAPE and RMSE

---

## 🛠️ Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels
