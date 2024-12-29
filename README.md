Ticket Count Prediction

Overview

This project forecasts ticket volumes using historical data to optimize resource allocation and improve operational efficiency. Built with Python, it employs time-series forecasting techniques.

Features

Data preprocessing and cleaning.

Time-series forecasting using Holt-Winters Exponential Smoothing.

Evaluation with Mean Absolute Error (MAE).

Visualization of predictions.

Technologies Used

Python, Pandas, Numpy, Statsmodels, Matplotlib.

Steps to Run

Setup: Install dependencies with:

pip install pandas numpy statsmodels matplotlib

Upload Data: Upload your historical ticket data (e.g., ticket_data.csv) to Google Colab.

Run Code: Open main_code.ipynb in Google Colab and execute the cells step by step.

Evaluate: Review MAE and visualize results.

Outputs: Predictions saved in forecast_results.csv and model saved as holt_winters_model.pkl.

Files

main_code.ipynb: Implementation notebook.

forecast_results.csv: Predicted results.

holt_winters_model.pkl: Saved model.
