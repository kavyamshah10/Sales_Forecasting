📊 Sales Forecasting & Retail Analysis System
🔥 Project Overview
This project is an end‑to‑end Sales Forecasting and Retail Analysis System built using Machine Learning, Exploratory Data Analysis (EDA), and Streamlit.

It combines:

Data Cleaning & Feature Engineering

Exploratory Data Analysis (EDA) with 13 charts

Model Training & Evaluation (Linear Regression, Random Forest, XGBoost)

Forecasting future sales (2013) using recursive time‑series techniques

Interactive Streamlit App for model evaluation and forecasting

Power BI Dashboard for business storytelling

🚀 Features
📈 1. Model Evaluation (2012)
Automatic comparison of Actual vs Predicted Sales

Performance metrics:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score

Weekly aggregated sales visualization

🔮 2. Sales Forecasting (2013)
Predicts future sales using recursive forecasting

User can:

Select Store

Select number of weeks

Outputs:

Forecast graph

Prediction table

Downloadable CSV file

🧠 Machine Learning Approach
🔍 Models Compared
Linear Regression

Random Forest Regressor

XGBoost Regressor

📊 Evaluation Metrics
MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score

✅ Final Model Selected
XGBoost Regressor was chosen as the final model due to its superior performance.

🔧 Feature Engineering
Time‑based features: Year, Month, Week, Day, Day_of_week

Lag features: Lag_1 (previous week), Lag_7 (previous 7 weeks)

Rolling statistics: Rolling_mean_7 (7‑week average)

🔁 Forecasting Technique
The project uses Recursive Forecasting:

Predict next week sales

Add prediction to dataset

Use updated data for next prediction

Repeat for multiple future weeks

📊 Exploratory Data Analysis (EDA)
Correlation Heatmap → Weak negative correlation between sales and CPI/unemployment.

CPI vs Weekly Sales → Clusters around CPI values 140, 190, 220.

Fuel Price vs Weekly Sales → Sales remain stable despite fuel price changes.

Holiday vs Weekly Sales → Sales rise modestly during holidays.

Monthly Trend – 2010 → Dip in September, peak in December.

Monthly Trend – 2011 (2 charts) → Consistent upward momentum toward year‑end.

Monthly Trend – 2012 → Volatile peaks in March, June, August.

Total Sales by Year → Peak in 2011 (~2450M), decline in 2012 (~2000M).

Average Sales per Store → Wide variation; some exceed 2M weekly sales, others <0.5M.

Temperature vs Weekly Sales → Sales cluster between 0.5M–2.5M across temperatures.

Top 10 Stores → Store 20 leads with >300M, Store 39 lowest among top 10 (~200M).

Unemployment vs Weekly Sales → Weak relationship; cluster when unemployment is 6–9.

Sales by Day of Week → Day 4 median ~1M, with outliers up to 3.7M.

💡 Business Insights
Holiday promotions drive measurable sales increases.

CPI clusters suggest distinct consumer segments.

Fuel price, temperature, and unemployment fluctuations have limited impact.

Year‑end peaks highlight seasonal demand.

Sales decline in 2012 signals need for strategic adjustments.

Store‑level differences reveal potential for targeted strategies.

Top‑performing stores drive disproportionate revenue, suggesting benchmarking opportunities.

🛠 Tech Stack
Python: Pandas, Matplotlib, Seaborn, XGBoost

Streamlit: Interactive dashboards with metrics and forecasting

Power BI: Business storytelling dashboards

Live App:[https://salesforecasting-8ybrfwg4b7inofskgxhqgi.streamlit.app]