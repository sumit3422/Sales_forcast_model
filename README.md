🛍️ Sales Forecasting Project (Intermediate Data Science)
This project explores historical sales data to identify trends, visualize insights, and forecast future sales using time-series models like ARIMA and Linear Regression.

📊 Overview
This project was completed over 7–10 days and includes:

🧹 Data Cleaning & EDA
📈 Sales Trend Analysis
📍 Regional & Segment Insights
📊 Power BI Dashboard with Filters
🔮 Time Series Forecasting using ARIMA & Linear Regression
✅ MAPE Accuracy: ARIMA - 9.75%, Linear Regression - 36.58%
🧪 Tools & Technologies
Google Colab – for Python code & model building
Pandas, Plotly, Matplotlib – data wrangling and visualizations
Statsmodels, Scikit-learn – forecasting models
Power BI – interactive dashboard creation
GitHub – project version control
📉 Forecasting Approach
Resampled sales data to monthly granularity
Applied Linear Regression and ARIMA(p,d,q) models
Tuned ARIMA hyperparameters via grid search
Evaluated performance using MAPE (Mean Absolute Percentage Error)
📌 Dashboard Highlights (Power BI)
Sales by Category, Region, and Time
Filters for Date, Segment, and Category
Profit vs. Discount visualizations
Regional heatmaps and KPIs
Power BI .pbix file is included in the repository.

📂 Dataset
Source: Kaggle - Superstore Sales Dataset
Columns used:

Order Date, Ship Date, Sales, Profit, Region, Category, etc.
📚 Future Improvements
Add seasonal ARIMA (SARIMA) modeling
Use Prophet or XGBoost for richer forecasting
Include external factors (promotions, holidays, etc.)
Deploy model via Streamlit app or API
