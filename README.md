# Time_Series
## *This was a Time Series project for TripleTen. 👩🏽‍💻*
This project builds a time series forecasting model to help Sweet Lift Taxi optimize driver allocation by predicting the number of ride orders for the next hour. The primary objective was to develop a model with an RMSE ≤ 48 on the test set, ensuring forecasts are accurate enough to support staffing decisions during peak periods.

The raw data, provided at 10-minute intervals, was resampled to hourly frequency to capture relevant patterns. Exploratory analysis revealed a slight upward trend, daily seasonality, and spikes in late April and August, likely influenced by seasonal tourism.

Several machine learning models were evaluated, including Random Forest, XGBoost, LightGBM, and CatBoost. While Random Forest performed well on training data (RMSE = 8.32), XGBoost proved the most robust on unseen data, achieving an RMSE of 39.10 on the test set—well within the acceptable range.

The final model, XGBoost, offers accurate, generalizable predictions and serves as a reliable tool to guide driver deployment during high-demand periods.
## Skills Highlighted
🍂 Trends and Seasonality
🛑 Stationary Series
🔄 Resampling & Feature Engineering
🛼 Rolling Mean & Autoregressive Moving Average
📆 Time Series Differences & Forecasting
💯 Model Training, Selection, Autoregression, & Forecast Accuracy
## Installation & Usage
* This project uses pandas, numpy, matplotlib.pyplot, seaborn, time, lightgbm, catboost, xgboost, sklearn, statsmodels.tsa.seasonal, and pmdarima.  It requires python 3.11.7.
