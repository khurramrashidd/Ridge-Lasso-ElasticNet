# Ridge, Lasso, and ElasticNet Regression    

This project demonstrates **linear regression with regularization** using **Ridge (L2)**, **Lasso (L1)**, and **ElasticNet (L1 + L2)** models in scikit-learn.

## Overview
- Synthetic regression data generated with `make_regression`
- Features standardized using `StandardScaler`
- Models trained and evaluated using **MSE** and **R² score**
- Comparison of model performance in a summary table

## Models Used
- **Ridge Regression** – L2 regularization
- **Lasso Regression** – L1 regularization (feature selection)
- **ElasticNet** – Combination of L1 and L2 regularization

## Requirements
- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn

Install dependencies:
```bash
pip install numpy pandas matplotlib scikit-learn
