# house-price-prediction with Linear Regression & LSTM

This project uses machine learning and deep learning techniques to predict housing prices in the USA. It begins with exploratory data analysis and a linear regression model, followed by an LSTM-based deep learning approach for enhanced prediction capabilities.

---

## Overview

- Dataset: `USA_Housing.csv` (contains income, house age, room counts, population, etc.)
- Models Used:
  - Linear Regression: For a basic prediction benchmark.
  - LSTM (Long Short-Term Memory): Deep learning model for sequential and pattern-based price prediction.
- Evaluation Metrics: MAE, MSE, RMSE

---
## Installation
To run this project, make sure you have Python installed. You can install all required libraries using the commands below:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn keras tensorflow


## Exploratory Data Analysis (EDA)

- Pairplots and heatmaps to study feature correlation
- Histogram of target variable (`Price`)
- Feature vs. target relationships visualized

---

##  Machine Learning (Linear Regression)

- Splits data into train/test sets
- Trains a `LinearRegression()` model
- Displays coefficients and intercept
- Provides a baseline for comparison

---

## Deep Learning (LSTM Model)

- Scales and reshapes input data for LSTM
- Builds a deep LSTM model with dropout layers
- Trains the model on the dataset
- Predicts and compares with actual values

---

##  Visualization

- **Actual vs Predicted Prices (Scatter plot)**
- **Residual Error Distribution**
- **Time-series Price Comparison**

---

## Evaluation Metrics

```text
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
