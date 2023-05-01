![](UTA-DataScience-Logo.png)

# Store Sales Forecasting

## Project Description
This project aims to forecast the sales of various stores using time series forecasting techniques. The dataset used is a publicly available [Store Sales Data](https://www.kaggle.com/c/rossmann-store-sales/data) from Kaggle which contains historical sales data for 1,115 Rossmann stores. The dataset includes various features such as the store ID, day of the week, promotional events, holidays, and competitor data. In addition, we also used the publicly available [Oil Prices Data](https://www.kaggle.com/mabusalah/brent-oil-prices) from Kaggle.

## Project Approach



  * **Definition of the tasks / challenge:**  The task, as defined by the Kaggle challenge is to use the provided dataset of Store Sales Forecasting, to develop an algorithm to implment a model that will output an accurate prediction for sales.

- **Performing Steps:** In this step, we first inspected the dataset and removed any missing values and outliers. We also converted the categorical variables to numerical variables using One-Hot Encoding. 

 
- **Data Cleaning and Preprocessing:** In this step, we first inspected the dataset and removed any missing values and outliers. We also converted the categorical variables to numerical variables using One-Hot Encoding. 

- **Exploratory Data Analysis (EDA):** We performed EDA to get a better understanding of the data, identify any patterns or trends, and create visualizations that can help us better understand the data. 


- **Time Series Forecasting:** We used the ARIMA model and Facebook's Prophet library to forecast the sales of the stores. We also evaluated the performance of the models using various metrics such as Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), and Symmetric Mean Absolute Percentage Error (SMAPE).

## Files
- `store_sales_time_series_forcasting.ipynb`: Jupyter notebook containing the code used for this project.
- `train.csv`: Contains the training set for the sales data.
- `test.csv`: Contains the test set for the sales data.
- `store.csv`: Contains the store information for each store ID in the sales data.
- `oil.csv`: Contains the oil prices data used in the analysis.



## What is Regression Analysis?
Predictive modelling techniques such as regression analysis may be used to determine the relationship between a dataset’s dependent (goal) and independent variables. It is widely used when the dependent and independent variables are linked in a linear or non-linear fashion, and the target variable has a set of continuous values. Thus, regression analysis approaches help establish causal relationships between variables, modelling time series, and forecasting. Regression analysis, for example, is the best way to examine the relationship between sales and advertising expenditures for a corporation.
Types of Regression Models Analysis / Different Regression Models
1. Linear Regression
2. Logistic Regression
3. Polynomial Regression
4. Ridge Regression
5. Lasso Regression
6. Quantile Regression

## Our Approach for Forecast 
 - **Linear Regression**
The most extensively used modelling technique is linear regression, which assumes a linear connection between a dependent variable (Y) and an independent variable (X). It employs a regression line, also known as a best-fit line. The linear connection is defined as Y = c+m*X + e, where ‘c’ denotes the intercept, ‘m’ denotes the slope of the line, and ‘e’ is the error term.
The linear regression model can be simple (with only one dependent and one independent variable) or complex (with numerous dependent and independent variables) (with one dependent variable and more than one independent variable).
 

- **Splitting Dataset for Training and Testing**
- 1)Training Data
The observations in the training set form the experience that the algorithm uses to learn. In supervised learning problems, each observation consists of an observed output variable and one or more observed input variables.
- 2) Test Data
The test set is a set of observations used to evaluate the performance of the model using some performance metric. It is important that no observations from the training set are included in the test set. If the test set does contain examples from the training set, it will be difficult to assess whether the algorithm has learned to generalize from the training set or has simply memorized it.


## Summary of Workdone

### Data

* Data:
  * Type: Text Data
  * Total Files :7 different files to Analyse
  * Size: ~118 MB
  * Instances: 10,48,576 training data, 28,513 testing images

## Model Evaluation

- **Linear Regression  Results**
![](Results.png)



## Conclusion
Through the analysis, we found that both the ARIMA model and Prophet library are capable of producing reasonably accurate forecasts for the sales of the stores. However, Prophet performed better in this case, producing a lower RMSE, MAPE, and SMAPE. We also found that holidays, promotions, and competition play a significant role in the sales of the stores. Based on the insights gained from the analysis, we can help the stores optimize their sales by implementing better promotional and pricing strategies during holidays and competitions.

## Contributors
- Revan Thakkar

## Acknowledgments
- Data provided by Rossmann Store Sales and Brent Oil Prices datasets from Kaggle.
- Inspiration, code snippets, etc.
