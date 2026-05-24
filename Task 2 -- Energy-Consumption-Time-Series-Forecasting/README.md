# Task 2: Energy Consumption Time Series Forecasting

## 📌 Objective
Build a predictive framework to forecast short-term household active power usage profiles based on historical, time-sequenced measurements.

## 📊 Dataset
* **Source:** Individual Household Electric Power Consumption Dataset

## 🛠️ Implementation Workflow
1. **Datetime Index Management:** Parsed data streams into chronological datetime formatting, handling missing intervals, and resampling data points cleanly.
2. **Temporal Feature Engineering:** Extracted granular time-based features (including hour indices, day-of-week variables, and weekday vs. weekend flags) to identify cyclical consumption spikes.
3. **Forecasting Model Architecture:** Developed and trained three distinct forecasting methodologies:
   * Classical statistical models (**ARIMA**)
   * Additive regression frameworks (**Prophet**)
   * Gradient-boosted decision tree architectures (**XGBoost**)
4. **Performance Evaluation:** Validated predictions using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) metrics to establish modeling accuracy.
5. **Visualization Profiles:** Generated time-series overlay plots mapping actual household energy consumption values against predicted trends across test horizons.

## 🚀 Key Skills Demonstrated
* Time Series Resampling & Index Alignment
* Chronological Feature Engineering
* Statistical vs. Machine Learning Forecast Evaluation (ARIMA vs. Prophet vs. XGBoost)
* Sequential Trend Visualization
