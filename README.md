# ETF-Price-Prediction

# Project Overview
Exchange Traded Funds (ETFs) offer a cost-effective alternative to mutual funds, gaining popularity due to their passive approach and lower fees. This project aims to analyze the changes in ETF prices, explore future investment opportunities, and predict closing prices using various algorithms.

# Objectives
- Analyze historical changes in ETF prices.
- Explore future investment opportunities in ETFs.
- Predict the closing price of ETFs using multiple algorithms and evaluate their accuracy.

# Motivation
The motivation behind this project is to:
- Provide data-driven insights to convince investors about the potential of ETFs.
- Develop a predictive model that assists in forecasting ETF prices.
- Analyze the viability of ETFs as a beneficial investment option.

# Data Collection and Preparation

## Data Sources
- ETFs.csv:Contains general information about various ETFs.
- ETF_prices.csv:Contains historical price data of ETFs.

## Data Importing
- Imported datasets using the `read_csv()` function from the Pandas library.

## Data Cleaning
- Dropped unnecessary columns from ETF_prices.csv using the `drop()` function.
- Merged `ETFs.csv` and `ETF_prices.csv` after handling null values.

## Data Visualization
- Visualized the dataset using various columns and attributes to identify trends and patterns.

## Algorithms and Models
To predict the closing prices of ETFs, the following algorithms were used:
- Random Forest Regressor
- XGBoost
- Gradient Boosting Regressor
The performance and consistency of these models were evaluated to determine the best approach for price prediction.

## Results
- The models were trained and tested on the historical ETF price data.
- The performance of each algorithm was evaluated based on accuracy and consistency.
- Insights and visualizations were generated to support investment decisions in ETFs.

## Conclusion
This project demonstrates the potential of using machine learning algorithms to predict ETF prices and provide valuable insights for investors. The Random Forest Regressor, XGBoost, and Gradient Boosting Regressor models were effective in analyzing historical data and forecasting future prices.



