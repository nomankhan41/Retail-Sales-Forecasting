# Retail-Sales-Forecasting
📌 Project Overview
This project focuses on forecasting retail sales using time series models and machine learning algorithms. The dataset consists of daily sales data, and the goal is to predict future sales accurately using ARIMA, SARIMA, and XGBoost.

🚀 Technologies Used
Python (Data Analysis & Modeling)

Pandas & NumPy (Data Manipulation)

Matplotlib & Seaborn (Visualization)

Statsmodels (ARIMA & SARIMA Models)

XGBoost (Machine Learning)

Scikit-Learn (Feature Scaling & Evaluation)

📊 Dataset
Time Period: Daily Sales Data

Features Used: Date, Total Sales, Day of the Month, Month, Weekday

🏆 Models Implemented & Performance
Model	Mean Absolute Error (MAE)
ARIMA	811
SARIMA	802
XGBoost	902
SARIMA achieved the lowest error, making it the most effective model for this dataset.

📈 Results & Visualization
The models' predictions were visualized against actual sales data to analyze accuracy.

ARIMA & SARIMA capture sales trends but struggle with high fluctuations.

XGBoost performed decently but had higher error due to feature limitations.

🔍 Challenges & Improvements
Error Reduction: Optimizing hyperparameters to minimize forecasting error.

Feature Engineering: Incorporating additional external factors (e.g., promotions, holidays).

Deep Learning: Exploring LSTM or Transformer-based models for improved accuracy.
