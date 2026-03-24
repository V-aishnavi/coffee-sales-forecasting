# Coffee-Sales-Forecasting
Coffee Sales Forecasting using Machine Learning

# ☕ Coffee Sales Forecasting Using Machine Learning

## 📌 Project Overview

This project focuses on analyzing coffee shop sales data and building machine learning models to forecast daily revenue. It combines data analysis, feature engineering, predictive modeling, and dashboard visualization to deliver actionable business insights.

---

## 🎯 Objectives

- Analyze historical coffee sales trends  
- Identify top-performing products  
- Forecast daily revenue using machine learning models  
- Build an interactive dashboard for decision-making  

---

## 📂 Dataset

The dataset contains transaction-level coffee sales data, including:

- Date  
- Coffee Type  
- Revenue  

The data was preprocessed and aggregated into **daily revenue** for time-series forecasting.

---

## 🔍 Exploratory Data Analysis (EDA)

Key insights derived from analysis:

- Daily revenue shows noticeable fluctuations with periodic peaks  
- Monthly trends indicate variation in sales performance  
- Certain coffee products consistently generate higher revenue  
- Weekend sales patterns differ from weekday trends  

---

## 🤖 Machine Learning Models

The following models were implemented and evaluated:

- Linear Regression  
- Random Forest  
- Gradient Boosting  
- XGBoost  

### 📊 Model Performance Summary

## 🤖 Model Performance Comparison

| Model | MAE | RMSE | R² Score |
|------|------|------|---------|
| Linear Regression | 108.40 | 133.13 | 0.32 |
| Random Forest | 105.42 | 126.02 | 0.39 |
| Gradient Boosting | 114.49 | 140.18 | 0.24 |
| XGBoost | 114.06 | 139.28 | 0.25 |

> 📌 **Best Model:** Random Forest demonstrated the most reliable performance for this dataset.

---

## 📈 Visualizations

### 📅 Revenue Trend
![Revenue_Trend] (Images/revenue_trend.png)
### ☕ Product Analysis
![Product_Analysis] ( Images/product_analysis.png)

### 📊 Model Comparison
![Model_Comparison] (Images/model_comparison.png)

### 📊 Dashboard
![Dashboard] (Images/dashboard.png)

---

## 📊 Dashboard Insights

An interactive dashboard was created using Power BI to provide:

- Total Revenue, Transactions, and Average Daily Revenue  
- Daily revenue trend analysis  
- Monthly performance comparison  
- Revenue by product category  

---

## 🛠️ Technologies Used

- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- XGBoost  
- Plotly & Dash  
- Power BI  

---

## 🚀 Key Learnings

- Time-series feature engineering (lags, rolling averages)  
- Model comparison and evaluation techniques  
- Importance of feature importance analysis  
- Building business-focused dashboards  

---

## 🔮 Future Improvements

- Incorporate external factors (weather, holidays, promotions)  
- Use advanced time-series models (ARIMA, LSTM)  
- Hyperparameter tuning for improved accuracy  
- Deploy model as a web application  

---

## 📌 Conclusion

- Revenue shows strong variability influenced by time-based patterns  
- Tree-based models outperform linear models for this dataset  
- Feature engineering significantly improves prediction performance  
- Dashboard enables clear business decision-making  

---
