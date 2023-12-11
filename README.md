# Heart Rate Forecasting Project
Introduction
This project aims to predict heart rates for the next two weeks using four different forecasting models: Facebook Prophet, ARIMA, Linear Regression, and Random Forest. The prediction models take into account parameters such as time of measurement, age, and activity/resting state. The project also includes a clear backtest based on each of the forecasts and implements an alert system to notify of values outside predefined thresholds.

Dataset
The heart rate data used for this project is obtained from [source]. The dataset includes information on the time of measurement, age, heart rate, and activity/resting state. The normal heart rate range is defined with an upper threshold of 100 and a lower threshold of 60.

Dataset Cleaning
The dataset is cleaned to extract relevant information, and missing or inconsistent values are handled appropriately.

Forecasting Models
1. Facebook Prophet
[Description of Facebook Prophet model implementation]

2. ARIMA (AutoRegressive Integrated Moving Average)
[Description of ARIMA model implementation]

3. Linear Regression
[Description of Linear Regression model implementation]

4. Random Forest
[Description of Random Forest model implementation]

Backtesting
A thorough backtest is performed for each forecasting model to evaluate its accuracy against real data. This involves comparing the forecasted values with actual heart rate values over a specified historical period.

Visualization
All visualizations are created using Plotly for interactive and informative charts. The charts include time series plots of actual vs. predicted values, as well as other relevant visualizations for each model.

Alerts
An alert system is implemented to notify users if forecasted values fall outside the predefined heart rate thresholds (60 to 100 beats per minute).

Project Execution Plan
Data Preparation (Day 1-2):

Clean up heart rate data.
Extract relevant information (time, age, activity/resting state).
Model Training (Day 3-6):

Implement Facebook Prophet, ARIMA, Linear Regression, and Random Forest models.
Train each model on the prepared dataset.
Backtesting (Day 7-9):

Perform backtests for each model.
Visualization (Day 10-11):

Create interactive charts using Plotly.
Alert System (Day 12-13):

Set up an alert system for out-of-threshold values.
Documentation and Finalization (Day 14):

Document the project, including code comments.
Finalize and review the project.
Budget Proposal
The proposed budget for this project is $700, covering the implementation, testing, visualization, and documentation phases. The budget ensures the successful completion of the project within the specified timeframe.

Conclusion
This project aims to provide accurate and reliable heart rate predictions, backed by thorough testing and visualization. The implementation of an alert system adds an extra layer of awareness for values outside the normal heart rate range.

