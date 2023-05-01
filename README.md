![](UTA-DataScience-Logo.png)

# Store Sales Forecasting

## Project Description
This project aims to forecast the sales of various stores using time series forecasting techniques. The dataset used is a publicly available [Store Sales Data](https://www.kaggle.com/c/rossmann-store-sales/data) from Kaggle which contains historical sales data for 1,115 Rossmann stores. The dataset includes various features such as the store ID, day of the week, promotional events, holidays, and competitor data. In addition, we also used the publicly available [Oil Prices Data](https://www.kaggle.com/mabusalah/brent-oil-prices) from Kaggle.

## Project Approach
- **Data Cleaning and Preprocessing:** In this step, we first inspected the dataset and removed any missing values and outliers. We also converted the categorical variables to numerical variables using One-Hot Encoding. 

- **Exploratory Data Analysis (EDA):** We performed EDA to get a better understanding of the data, identify any patterns or trends, and create visualizations that can help us better understand the data. 

- **Time Series Forecasting:** We used the ARIMA model and Facebook's Prophet library to forecast the sales of the stores. We also evaluated the performance of the models using various metrics such as Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), and Symmetric Mean Absolute Percentage Error (SMAPE).

## Files
- `store_sales_time_series_forcasting.ipynb`: Jupyter notebook containing the code used for this project.
- `train.csv`: Contains the training set for the sales data.
- `test.csv`: Contains the test set for the sales data.
- `store.csv`: Contains the store information for each store ID in the sales data.
- `oil.csv`: Contains the oil prices data used in the analysis.

## Conclusion
Through the analysis, we found that both the ARIMA model and Prophet library are capable of producing reasonably accurate forecasts for the sales of the stores. However, Prophet performed better in this case, producing a lower RMSE, MAPE, and SMAPE. We also found that holidays, promotions, and competition play a significant role in the sales of the stores. Based on the insights gained from the analysis, we can help the stores optimize their sales by implementing better promotional and pricing strategies during holidays and competitions.

## Contributors
- Your name(s) here.

## Acknowledgments
- Data provided by Rossmann Store Sales and Brent Oil Prices datasets from Kaggle.
- Inspiration, code snippets, etc.
