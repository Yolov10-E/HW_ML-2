# Simple Regression Analysis

Luqman Ardiseno 13320021

This repository contains a simple regression analysis performed on a dataset of sales and advertising costs. The analysis aims to predict the advertising cost based on given sales values.

## Dataset

The dataset contains two columns:
- Sales (in million $)
- Advertising (in million $)

## Predictions

The predicted advertising costs for the given sales values are:
- For 50 sales: $77.83 million
- For 100 sales: $173.58 million
- For 150 sales: $269.32 million

## Model Evaluation

- RMSE (Root Mean Squared Error): 14.37
- R² Score: 0.40

## Files

- `simple_regression_analysis.py`: Python script to perform the regression analysis and make predictions.
- `SALES.txt`: The dataset used for analysis.

## How to Run

1. Clone the repository.
2. Ensure you have the necessary libraries installed (`pandas`, `numpy`, `sklearn`).
3. Run the script `simple_regression_analysis.py`.

```sh
python simple_regression_analysis.py
