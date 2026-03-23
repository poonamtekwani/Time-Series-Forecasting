# 📈 Wine Sales Forecasting & Demand Analysis using Time Series (Rosé & Sparkling)

## 📌 Project Overview
Designed and implemented advanced time series forecasting models to analyze and predict sales trends for Rosé and Sparkling wines. The project focuses on uncovering seasonality, evaluating multiple forecasting techniques, and delivering data-driven insights for strategic business planning.

---

## 🎯 Objectives
- Analyze historical sales patterns and seasonality  
- Forecast future demand (12-month horizon)  
- Compare multiple forecasting techniques  
- Provide actionable insights for revenue optimization and inventory planning  

---

## 📊 Dataset
- Monthly wine sales data (1980–1995)  
- Categories analyzed:
  - Rose Wine  
  - Sparkling Wine  
- ~187 time-series observations per dataset  

---

## ⚙️ Approach
- Time series preprocessing and feature extraction  
- Exploratory Data Analysis (trend, seasonality, distribution)  
- Decomposition (Additive & Multiplicative models)  
- Stationarity testing using Augmented Dickey-Fuller (ADF)  
- Differencing to achieve stationarity  
- Train-test split for model validation  

---

## 🤖 Models & Techniques
- Linear Regression (baseline model)  
- Moving Average & Exponential Smoothing  
- Holt-Winters (Triple Exponential Smoothing)  
- ARIMA (Manual & Auto)  
- SARIMA (Seasonal modeling)  

---

## 📈 Model Evaluation
- Evaluated using MSE, MAE, RMSE, and AIC  
- **ARIMA achieved best predictive accuracy (lowest error metrics)**  
- **SARIMA captured seasonal patterns effectively (lowest AIC)**  

---

## 🔍 Key Insights
- Strong seasonal trends: peak sales in December, lowest in January  
- Sparkling wine shows stable long-term demand  
- Rosé wine shows declining trend over time  
- Seasonal demand significantly influences sales performance  

---

## 💡 Business Impact
- Improves inventory planning and demand forecasting  
- Enables targeted marketing during low-demand periods  
- Supports strategic pricing and campaign planning  
- Helps optimize revenue through seasonal insights  

---

## 🛠️ Tech Stack
Python | Pandas | Statsmodels | Matplotlib  

---

## 📌 Conclusion
The project demonstrates how advanced time series models can be leveraged to generate accurate forecasts and actionable business insights, enabling data-driven decision-making in a competitive market environment.
