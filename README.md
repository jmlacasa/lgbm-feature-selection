# Feature Selection Pipeline using LGBM

## Description
This project is designed to analyze a vast array of technical indicators and assess their predictive power against a multiclass target variable (Y). It leverages the LightGBM (LGBM) machine learning framework for its efficient handling of large datasets and feature selection capabilities. The goal is to identify the most relevant technical indicators that contribute to accurate predictions in financial time series data.

## Key Features
- Comprehensive analysis of all indicators available in the `pandas_ta` library.
- Custom functions in `time_series_utils.py` for calculating lags, applying technical indicators, and overlapping different temporalities.
- Visualization of data and results using the `seaborn` library.
- Utilization of LightGBM for efficient feature selection and modeling.
- Model evaluation doing cross-validation, multi-class ROC AUC curves and various classification metrics

## Technologies Used
- pandas_ta: For a wide range of technical indicators.
- seaborn: For data visualization.
- LightGBM: For machine learning models.
- Custom utilities: Found in `time_series_utils.py` for enhanced time series analysis.

## Installation
Clone the repository and install the required libraries.
```bash
git clone https://github.com/jmlacasa/lgbm-feature-selection.git
cd [repository directory]
pip install -r requirements.txt
```
