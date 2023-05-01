![](UTA-DataScience-Logo.png)

# Project Title

Store Sales Forecasting

## Project Description

The goal of this project is to forecast the sales of a chain of stores based on historical sales data, macroeconomic variables, and special events. The data includes the historical sales of each store, as well as information about the stores' locations, types, and sizes. Additionally, external data on macroeconomic variables, such as GDP and inflation, is used to predict sales trends. Finally, data on special events, such as holidays and promotions, is also incorporated into the model.

## Data Sources

The following data sources were used in this project:

- `sales_train.csv`: historical sales data for each store and product
- `test.csv`: testing set used for Kaggle competition evaluation
- `stores.csv`: information about each store
- `items.csv`: information about each product
- `oil.csv`: historical oil prices (not included in this project)
- `holidays_events.csv`: information about special events

## Approach

1. Data cleaning and exploration
    - Outliers detection and removal
    - Missing values imputation
    - Feature engineering
2. Time series analysis
    - Stationarity check and transformation
    - Autocorrelation and partial autocorrelation analysis
3. Model selection and tuning
    - Baseline models (naive, seasonal naive, average)
    - Classical time series models (ARIMA, SARIMA)
    - Machine learning models (Random Forest, XGBoost)
4. Model evaluation and selection
    - Mean Absolute Percentage Error (MAPE) metric
    - Backtesting and cross-validation
    - Ensembling and stacking of models
5. Production deployment
    - Re-training on full dataset
    - Generating forecasts on new data
    - Automating data pipeline and model updates

## Tools and Technologies

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Statsmodels
- XGBoost
- Jupyter Notebook
- Git, GitHub

## Contributors

- Revan Thakkar (https://github.com/rdt2099) 

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
