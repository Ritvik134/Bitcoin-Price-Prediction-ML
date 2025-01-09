# Bitcoin Price Prediction using Machine Learning

A machine learning project that analyzes Bitcoin price trends and attempts to predict price movements using various ML algorithms.

## Project Overview

This project implements multiple machine learning models to predict Bitcoin price movements using historical OHLC (Open, High, Low, Close) data from 2014 to 2022. The project includes comprehensive data analysis, feature engineering, and model comparison.

## Features

- Historical Bitcoin price analysis using 8 years of data
- Feature engineering including quarter-end analysis
- Multiple ML model implementations (XGBoost, SVM, Logistic Regression)
- Detailed data visualization and correlation analysis
- Model performance comparison using ROC-AUC metrics

## Technologies Used

- Python 3.x
- Libraries:
  - pandas - Data manipulation and analysis
  - numpy - Numerical computing
  - scikit-learn - Machine learning algorithms
  - XGBoost - Gradient boosting
  - matplotlib/seaborn - Data visualization
  
## Data Analysis

The project includes:
- Exploratory Data Analysis (EDA) of Bitcoin prices
- Analysis of price trends and patterns
- Feature correlation studies
- Quarter-end impact analysis

## Model Implementation

Three machine learning models were implemented and compared:
- Logistic Regression
- Support Vector Machine (SVM) with polynomial kernel
- XGBoost Classifier

## Key Findings

- Identified significant price volatility patterns
- Analyzed quarter-end effects on Bitcoin prices
- Discovered high correlation between OHLC features
- Models achieved baseline performance, highlighting the complexity of cryptocurrency price prediction

## Installation and Setup

1. Clone the repository
2. Install required packages:
```bash
pip install pandas numpy sklearn xgboost matplotlib seaborn
```
3. Download the Bitcoin historical price dataset
4. Run the Jupyter notebook

## Future Improvements

- Include additional technical indicators
- Implement deep learning models
- Add real-time price data integration
- Enhance feature engineering

