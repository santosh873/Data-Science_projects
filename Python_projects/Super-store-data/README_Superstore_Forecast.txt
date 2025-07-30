📦 Superstore Monthly Sales Forecasting (2014–2018)

📘 Overview
This project analyzes and forecasts monthly average sales for a Superstore dataset using two time series models:
1. Prophet (by Facebook/Meta)
2. SARIMA (Seasonal ARIMA)

Forecasting is done for the year 2017 (evaluation) and extended to 2018 (future prediction) using SARIMA.

📁 Dataset
- Source: Superstore sales data (Superstore.csv)
- Filtered Years: 2014 to 2017
- Target Column: Sales
- Monthly average sales (resample('ME').mean())

🔧 Tools & Libraries
- pandas, numpy
- matplotlib
- prophet
- statsmodels (SARIMA)
- sklearn.metrics (for MAE, RMSE)

🧠 Methodology

📅 Data Preparation
- Convert Order Date to datetime
- Filter data between 2014-01-01 and 2017-12-31
- Resample sales to monthly average

🔮 Prophet Forecast
- Train: 2014–2016
- Test: 2017
- Prophet model trained and forecasted
- Evaluation using MAE and RMSE

📈 SARIMA Forecast
- Model: (1,1,1)(1,1,1,12)
- Step 1: Train on 2014–2016 → Predict 2017
- Step 2: Retrain on 2014–2017 → Predict full year 2018
- Exported 2018 forecast to Excel

📊 Evaluation (2017)

| Model   | MAE     | RMSE    |
|---------|---------|---------|
| Prophet | 46.40   | 59.82   |
| SARIMA  | 49.83  | 58.04  |

📅 Forecast (2018)
  (Values exported to forecast_2018_sales.xlsx)

📈 Visuals Included
- Line chart: Monthly average sales (2014–2017)
- Prophet: Forecast vs Actual for 2017
- SARIMA: Forecast vs Actual for 2017
- SARIMA: Forecast for full year 2018

📌 File Structure
- superstore_forecast.ipynb – Full project code
- Superstore.csv – Input dataset
- forecast_2018_sales.xlsx – SARIMA forecast output
- README.txt – Project documentation (this file)

✅ Conclusion
Both Prophet and SARIMA provided competitive forecasts for 2017, with SARIMA extended to forecast 2018 sales.
Time series modeling helps Superstore stakeholders anticipate future trends and manage inventory, marketing, and operations better.
