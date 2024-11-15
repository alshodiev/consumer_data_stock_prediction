# Swipe Right on Returns: Forecasting Stocks with Consumer Transaction Trends

## Overview
This personal project explores the relationship between credit card spending data and daily stock returns for 100 unique stocks. Using data on consumer transaction trends across different user cohorts, we investigate how spending patterns can forecast stock returns. The project applies various modeling techniques, including linear regression, Random Forest, and Lasso regression, to understand the predictive power of spending data on stock returns.

## Contents
- **Data Preprocessing**: Cleaning and transforming credit card spending data, stock metadata, and stock returns.
- **Feature Engineering**: Creating features from spending data, including cohort and sector-based metrics.
- **Modeling**: Building and evaluating models to forecast stock returns based on spending data.
- **Results Analysis**: Analyzing model performance, sector performance, and trading strategies.

## Files
- `final_report.pdf` : Contains my written analysis
- `Modeling and Analysis.ipynb` : Contains the modeling along my analysis step by step
- `README.md`: Overview of the project (this file).

## Key Findings
- **Forecast Power**: Smoothing the "total spend" variable shows a strong forecasting power of 0.8, indicating spending trends are effective predictors of stock returns.
- **Model Performance**: The models achieved low RMSE and MAE values, showing they capture significant variation in stock returns.
- **Sector Analysis**: Some sectors, particularly those directly influenced by consumer spending, perform better in predictive models.

## Future Work
- Potential improvements include exploring additional predictors, adjusting lag structures, and applying non-linear models. See Notebook for more

