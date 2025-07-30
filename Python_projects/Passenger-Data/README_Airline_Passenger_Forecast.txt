✈️ Airline Passenger Forecasting Using SARIMA

📘 Overview
This project forecasts monthly airline passenger numbers using SARIMA modeling. The dataset spans from 1949 to 1960,
and the forecast extends into 1961.

📁 Dataset
- Source: https://raw.githubusercontent.com/jbrownlee/Datasets/master/airline-passengers.csv
- Columns:
  - Month: Monthly time period
  - Passengers: Number of passengers

🔧 Tools & Libraries
- pandas, numpy
- matplotlib
- statsmodels (SARIMAX)
- sklearn.metrics (for MAE, RMSE)

🧠 Methodology

1. Load the dataset and convert the Month column to datetime.
2. Set Month as the index and visualize the time series.
3. Check for stationarity and apply differencing as needed.
4. Fit SARIMA model with order (1,1,1)(1,1,1,12).
5. Split into training (1949–1959) and testing (1960).
6. Forecast values for 1960 and evaluate performance.
7. Retrain model on full dataset and forecast for 1961.

📊 Evaluation (1960)

| Metric | Value   |
|--------|---------|
| MAE    | 16.67   |
| RMSE   | 21.62  |

(Replace XX.XX with your actual results)

📅 Forecast Output (1961)
   Predicted Passengers for 1961:
   1961-01-01    423.220775
   1961-02-01    406.433567
   1961-03-01    467.547433
   1961-04-01    457.478941

📈 Visuals Included
- Original time series plot
- Differenced time series
- ADF test results before and after differencing
- Forecast vs Actual (1960)
- Forecast for 1961 with confidence interval

📌 File Structure
- airline_passenger_forecast.ipynb – Jupyter notebook with full code
- word document conatain python code snap 
- README.txt – This documentation file

✅ Conclusion
SARIMA successfully captured the seasonal trend in airline passenger growth. The 1961 forecast can help model
future airline demand based on past trends.
