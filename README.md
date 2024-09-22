# Sales Forecast

This repository contains a Sales Forecasting project aimed at predicting future sales based on historical data using various machine learning models. The project involves data preprocessing, time series analysis, model training, and evaluation.

**Project Overview**
Sales forecasting is a critical aspect of business planning. Accurate predictions of future sales enable businesses to make informed decisions about inventory management, budgeting, and marketing strategies. In this project, we utilize historical sales data to build models that forecast future sales.

**Data Description**
The dataset contains monthly sales data for a store, including the following columns:

date: Date of the sales record.
store: Store identifier.
item: Item identifier.
sales: Number of items sold.

**Data Summary:**
Number of records: 913,000
Columns: 4 (date, store, item, sales)
Memory usage: 27.9+ MB
Project Steps

**Data Preprocessing:**
Convert the date column to a timestamp format.
Create a new column for the difference in sales from the previous month (sales_diff).
Drop any missing values.

**Feature Engineering:**
Generate lag features for the past 12 months of sales differences.

**Modeling:**
Implement various models including:
Linear Regression
Random Forest Regressor
XGBoost Regressor
LSTM (Long Short-Term Memory) Neural Network

**Evaluation:**
Evaluate the models using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) score.
Visualize the actual versus predicted sales to assess model performance.

**Key Results**
Linear Regression Performance:
MSE: 16221.272
MAE: 12433.184
R2: The model showed a good fit with a significant R-squared value.

**More Projects**
To see more of my projects, please visit my portfolio: **www.jaydugad.com**

**Contributing**
Contributions are welcome! Please feel free to submit a Pull Request.

**License**
This project is licensed under the MIT License - see the LICENSE file for details.
