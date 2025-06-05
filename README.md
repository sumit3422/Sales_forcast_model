Sales Forecasting Project

This project analyzes historical sales data to identify trends, visualize insights, and forecast future sales using time-series models like ARIMA and Linear Regression. The project was completed in 7–10 days as an intermediate data science exercise.

📊 Project Overview





Objective: Analyze historical sales data, uncover trends, and predict future sales.



Key Components:





🧹 Data Cleaning & EDA: Handled missing values, outliers, and performed exploratory data analysis.



📈 Sales Trend Analysis: Identified patterns in sales over time.



📍 Regional & Segment Insights: Analyzed sales by region, category, and customer segment.



📊 Power BI Dashboard: Built an interactive dashboard with filters for date, segment, and category.



🔮 Time Series Forecasting: Implemented ARIMA and Linear Regression models for sales forecasting.



✅ Model Performance:





ARIMA MAPE: 9.75%



Linear Regression MAPE: 36.58%

🧪 Tools & Technologies





Google Colab: Python environment for data analysis and model building.



Pandas, Plotly, Matplotlib: Data wrangling and visualizations.



Statsmodels, Scikit-learn: Time-series and regression modeling.



Power BI: Interactive dashboard creation.



GitHub: Version control for project files.

📉 Forecasting Approach





Resampled sales data to monthly granularity for consistency.



Applied Linear Regression and ARIMA(p,d,q) models.



Tuned ARIMA hyperparameters using grid search to optimize performance.



Evaluated models using Mean Absolute Percentage Error (MAPE).

📌 Dashboard Highlights (Power BI)





Visualizations:





Sales by Category, Region, and Time.



Profit vs. Discount analysis.



Regional heatmaps and KPIs.



Interactivity:





Filters for Date, Segment, and Category.



File: The .pbix file is included in the repository.

📂 Dataset





Source: Kaggle - Superstore Sales Dataset



Columns Used:





Order Date, Ship Date, Sales, Profit, Region, Category, etc.

📚 Future Improvements





Implement seasonal ARIMA (SARIMA) for better handling of seasonality.



Explore Prophet or XGBoost for advanced forecasting.



Incorporate external factors like promotions or holidays.



Deploy the model as a Streamlit app or API for real-time predictions.
