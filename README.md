# Swipe Right on Returns: Forecasting Stocks with Consumer Transaction Trends

## Overview
This personal project explores the relationship between credit card spending data and daily stock returns for 100 unique stocks. Using data on consumer transaction trends across different user cohorts, we investigate how spending patterns can forecast stock returns. The project applies various modeling techniques, including linear regression, Random Forest, and Lasso regression, to understand the predictive power of spending data on stock returns.

## Contents
## Notebook Contents

- [**1. Data Loading and Exploration**](#set_up)
    - [Load the Data](#load_data)
    - [Utils](#utils)
    - [Perform Exploratory Data Analysis (EDA)](#eda)
        - [Data Description + Anomalies](#data_description)
        - [Visualizations](#visualizations)
- [**2. Constructing the Spend Time Series**](#spend_time_series)
    - [Aggregate Spend Data and Plot Time Series](#spend_data)
    - [Analyze Relationship with Active Cohorts](#active_cohort_analysis)
- [**3. Seasonality Analysis and Correction**](#seasonality_correction)
    - [Detect Seasonality](#detect_seasonality)
        - [Time-Series Decomposition](#decomposition)
        - [Stationarity Test](#stationarity_test)
        - [Autocorrelation Analysis](#autocorrelation_analysis)
    - [Baseline Modeling - Implement Seasonality Correction](#implement_correction)
- [**4. Improving the Baseline Model with Feature Engineering**](#feature_engineering)
    - [Apply Smoothing Techniques](#smoothing_applied)
    - [Incorporate Lagged Variables](#lagged_var)
    - [Model Training and Evaluation](#train_eval)
    - [Feature Engineering](#additional_features)
    - [Visualizing Feature Importances](#feature_imp)
    - [Final Modeling](#ht)
- [**6. Sector Performance Analysis**](#sector_analysis)
    - [Evaluate Model by Sector](#model_sector_eval)
    - [Interpretation and Sector Inclusion Decision](#inclusion_exclusion)
- [**7. Trading Strategy Development**](#trading_strategy)
    - [Signal Generation Methods](#signal_generation)
    - [Cumulative PnL](#cum_pnl)
- [**9. Additional Data Sources**](#additional_data)
- [**10. Conclusion and Recommendations**](#conclusion)

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

