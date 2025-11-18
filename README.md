🌬️ Wind Turbine SCADA Analysis – Short README
📌 Overview

This project analyzes Wind Turbine SCADA data to understand turbine performance, visualize patterns, detect anomalies, and generate an AI-based performance score.
Dataset: Wind Speed, Active Power, Theoretical Power Curve, Wind Direction, Timestamp


Task 1 – EDA

Cleaned and parsed Date/Time

Checked missing/outlier values

Visualized:

Time-series trends

Wind Speed vs Active Power (power curve)

Correlation heatmap

Monthly power trends

Task 2 – Forecasting

Converted data into time-series format

Created windowed sequences

Built regression/time-series models to forecast:

Active Power

Wind Speed

Theoretical Power

Wind Direction

Evaluated using RMSE, MAE, R²

Plotted actual vs predicted values

Task 3 – Anomaly Detection

Compared Actual Power vs Theoretical Power

Used Z-score/IQR to detect underperformance

Plotted anomalies for interpretation

Task 4 – AI Performance Scoring

Calculated Performance Score:

Score = (Actual Power / Theoretical Power) × 100


Classified turbine as Good / Moderate / Poor

Generated automated suggestions

Visualized performance score over time

🛠 Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Google Colab



Run each task step-by-step

View plots, forecasts, anomalies, and performance score
