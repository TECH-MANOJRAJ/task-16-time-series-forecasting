# 📈 Task 16 – Time Series Forecasting

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Forecasting](https://img.shields.io/badge/Time%20Series-Forecasting-orange)
![Status](https://img.shields.io/badge/Task-Completed-brightgreen)

---

## 🚀 Project Overview

This project focuses on Time Series Forecasting using historical monthly car sales data.

The objective was to:
- Analyze trend and seasonality
- Build forecasting models
- Evaluate prediction accuracy
- Forecast future sales values

This task was completed as part of a Data Analyst Internship.

---

## 📊 Dataset Information

Dataset: Monthly Car Sales  
Source: Brownlee GitHub Dataset  
Frequency: Monthly  
Time Period: 1956 – 1968  

Columns:
- Date
- Sales

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- Matplotlib
- Statsmodels (Holt-Winters Model)
- Scikit-learn

---

## 🔍 Project Workflow

1. Loaded dataset and converted Date column to datetime
2. Set Date as index for time-series analysis
3. Visualized sales trend over time
4. Applied rolling mean to check seasonality
5. Split data into Train (80%) and Test (20%)
6. Built forecasting models:
   - Exponential Smoothing (Trend Only)
   - Holt-Winters (Trend + Seasonality)
7. Evaluated model using:
   - MAE (Mean Absolute Error)
   - MAPE (Mean Absolute Percentage Error)
8. Forecasted future 12 months of sales
9. Exported results to CSV files

---

## 📈 Model Performance

| Metric | Value |
|--------|--------|
| MAE    | XX |
| MAPE   | XX % |

Replace XX with your actual results.

Lower MAE and MAPE indicate better model performance.

---

## 📁 Repository Structure

task-16-time-series-forecasting/
│
├── task16_forecasting.ipynb
├── forecast_output.csv
├── future_12_months_forecast.csv
├── forecast_report.txt
└── README.md

---

## 📌 Key Insights

- The dataset shows strong yearly seasonality.
- Holt-Winters model performed better than trend-only model.
- Forecasting helps in business planning and demand estimation.

---

## 🎯 Business Impact

Time-series forecasting can support:

- Inventory planning
- Demand forecasting
- Revenue prediction
- Production optimization

---

## 👨‍💻 Author

MANOJRAJ G
Data Analyst Intern  
