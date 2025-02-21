# Traffic Analysis using Machine Learning

## Overview

This project analyzes traffic patterns using machine learning models to predict traffic congestion levels. It includes data preprocessing, feature engineering, and model evaluation with different regression algorithms.

## Features

- Data Preprocessing: Handling missing values, scaling, and feature selection.

- Machine Learning Models:

  1. Linear Regression

  2. Decision Tree Regressor

  3. Support Vector Regressor (SVR)

  4. Heterogeneous Ensemble Model

- Model Evaluation: Performance metrics such as RMSE, R² Score, and Mean Absolute Error.

- Visualization: Graphical analysis of model predictions.

## Dependencies

Install required libraries using:

pip install pandas numpy matplotlib scikit-learn

## Dataset

The dataset (traffic_index.csv) contains traffic congestion data, including:

- Datetime: Timestamp of recorded data.

- City: Location of traffic measurement.

- TrafficIndexLive: Traffic congestion percentage.

and more features...

## Usage

- Load the dataset and filter for the desired city (e.g., Riyadh).

- Preprocess the data, including handling missing values and scaling.

- Train machine learning models using different regression techniques.

- Evaluate models with standard performance metrics.

- Visualize results to interpret predictions.


## Model Comparisons


| Model               | RMSE  | R² Score | MSE  | MAE  |
|---------------------|------|---------|------|------|
| Linear Regression  | 2.0074 | 0.9879    | 4.0295 | 1.4648 |
| Decision Tree      | 2.2804 | 0.9843    | 5.2001 | 1.6694 |
| SVR                | 1.7197 | 0.9911    | 2.9574 | 1.1681 |
| Ensemble Model     | 1.7026 | 0.9913    | 2.8988 | 1.1534 |




## Visualization

The analysis includes plots for each model, showcasing actual vs. predicted traffic values.

Example plot for every model (actual vs. predicted traffic values)

<img width="424" alt="image" src="https://github.com/user-attachments/assets/6d89a4f4-ef80-4a2c-a4b1-a8da2b87f13c" />



