# Wine-Demand-Modeling-Count-Regression
Count regression modeling using Poisson and Negative Binomial approaches with feature engineering, missing data handling, and model comparison for wine sales prediction.
# Wine Demand Modeling using Count Regression

## Overview
This project develops predictive models for wine purchase counts using Poisson and Negative Binomial regression. The analysis includes data cleaning, missing value treatment, feature engineering, and model comparison for demand prediction.

## Dataset
- 12,795 observations
- 16 predictors including chemical properties, expert ratings, and marketing features
- Target variable: wine purchase count

## Data Preparation
- Replaced chemically impossible negative values with NA
- Created missing-value indicator variables
- Applied median and mode imputation
- Log-transformed highly skewed predictors
- Engineered interaction and ratio-based features

## Models Implemented
- Poisson Regression
- Negative Binomial Regression

## Model Evaluation
- Compared models using AIC, residual deviance, and RMSE
- Addressed overdispersion using Negative Binomial modeling
- Benchmarked against linear regression baseline

## Key Findings
- Expert ratings and label appeal significantly influence demand
- Acidity shows a negative relationship with sales
- Count models outperform linear regression for this dataset
