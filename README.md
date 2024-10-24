# Price Optimization Case Study

## Overview
This project aims to develop a dynamic pricing model that optimizes the prices of items to maximize revenue while remaining competitive in the market. The analysis includes examining current pricing strategies, competitor pricing, and sales performance, followed by the implementation of a dynamic pricing model.

## Table of Contents
- [1. Problem Statement](#1-problem-statement)
- [2. Dataset Overview](#2-dataset-overview)
- [3. Data Preprocessing](#3-data-preprocessing)
- [4. Exploratory Data Analysis (EDA)](#4-exploratory-data-analysis-eda)
- [5. Price Elasticity Analysis](#5-price-elasticity-analysis)
- [6. Modeling](#6-modeling)
- [7. Backtesting](#7-backtesting)
- [8. Results](#8-results)
- [9. Conclusion](#9-conclusion)


## 1. Problem Statement
- Analyze the current pricing strategy and its impact on sales and revenue.
- Compare our pricing strategy with that of the competition to identify gaps and opportunities.
- Develop a dynamic pricing model that adjusts prices based on factors such as competitor pricing, demand elasticity, and market trends.
- Implement and simulate the dynamic pricing model to compare its performance against the existing pricing strategy.

## 2. Dataset Overview
The dataset contains pricing information for various items sold at a retail store and their corresponding prices at competing stores. Key columns include:
- `Fiscal_Week_ID`: The fiscal week identifier.
- `Store_ID`: The store identifier.
- `Item_ID`: The item identifier.
- `Price`: The price of the item at our store.
- `Item_Quantity`: The quantity of the item sold.
- `Sales_Amount`: Sales amount after discounts.
- `Competition_Price`: The price of the item at a competing store.

## 3. Data Preprocessing
- Data cleaning and preprocessing steps included handling missing values, removing outliers, and creating new features such as price difference and moving averages.
- Data types were adjusted, and categorical variables were encoded for modeling.

## 4. Exploratory Data Analysis (EDA)
- Visualizations were created to analyze price distributions, sales trends, and correlations between variables.
- Key insights included the identification of strong correlations between our prices and competitor prices, as well as trends in sales amounts across different stores and items.

## 5. Price Elasticity Analysis
- Calculated price elasticity to understand how quantity demanded responds to price changes.
- Items were categorized into segments based on their elasticity, revealing opportunities for pricing strategies.

## 6. Modeling
- Implemented various machine learning models, including Random Forest and XGBoost, to predict optimal pricing.
- A stacking ensemble model was created to improve prediction accuracy.
- Hyperparameter tuning was performed using RandomizedSearchCV for model optimization.

## 7. Backtesting
- The model was backtested using historical data to evaluate its performance in predicting prices.
- Metrics such as RMSE, MAE, and R² were calculated to assess model accuracy.

## 8. Results
- The optimized pricing model significantly increased total revenue, with an observed revenue change of approximately **479.23%**.
- Visualizations were created to compare actual vs. predicted prices and to illustrate the improvements in revenue and sales volume.

## 9. Conclusion
This case study demonstrates the effectiveness of a dynamic pricing strategy in maximizing revenue while remaining competitive. The insights gained from the analysis can guide future pricing decisions and marketing strategies.


