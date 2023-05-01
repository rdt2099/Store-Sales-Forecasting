![](UTA-DataScience-Logo.png)

# Store Sales Time Series Forecasting

## Overview

This project is about forecasting sales for a store chain based on their historical sales data. The aim of this project is to develop a time series model to forecast sales for the next few months. The model will be trained on historical data and validated on a holdout test set.

## Data

The data for this project was obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Sales_Transactions_Dataset_Weekly). It consists of historical weekly sales data for 1,155 products across 39 different stores of a retail chain. The data spans from week 1 of 2011 to week 52 of 2013.

## Methodology

We will use the following methodology for this project:

1. Data Cleaning and Preparation
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Development
5. Model Evaluation and Selection
6. Forecasting and Validation

## Requirements

The following packages are required to run the code:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- statsmodels

## Usage

To run the code, follow these steps:

1. Clone the repository
2. Install the required packages
3. Open the Jupyter Notebook `store_sales_time_series_forcasting.ipynb`
4. Run each cell in order

## Results

The final model was able to achieve a mean absolute percentage error (MAPE) of 5% on the holdout test set, indicating good performance in predicting future sales.

## Conclusion

This project demonstrates the use of time series modeling to forecast future sales for a retail chain. The results show that accurate sales forecasting can be achieved using historical sales data and appropriate modeling techniques. Further research can be done to improve the model's performance and explore additional features for inclusion in the model.
