<<<<<<< HEAD
# UrbanCart — Milestone 1: Customer Spend Prediction

## Project Overview

UrbanCart is an e-commerce retailer that wants to predict how much each customer will spend in the following month.

This project develops and compares two supervised machine learning regression models:

1. Linear Regression
2. Random Forest Regression

The goal is to predict `NextMonthSpend` using customer activity and purchasing information.

## Dataset

The dataset contains 20,000 customer records.

Features:

- `MonthsActive`
- `AvgOrderValue`
- `NumOrdersLastQuarter`
- `Region`

Target:

- `NextMonthSpend`

## Methodology

The dataset was divided into:

- 80% training data
- 20% held-out test data

The test set was kept separate from model training.

Categorical `Region` data was encoded using one-hot encoding.

## Models

### Linear Regression

Used as an interpretable baseline for the continuous spending prediction problem.

### Random Forest Regression

Used as a more flexible model capable of capturing nonlinear relationships and interactions.

## Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R²

## Results

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 9.846 | 12.330 | 0.830 |
| Random Forest | 10.487 | 13.077 | 0.809 |

## Recommendation

Linear Regression was selected for this milestone because it produced lower MAE and RMSE and a higher R² on the held-out test set.

Although Random Forest provides greater modeling flexibility, that additional flexibility did not improve performance on this test set. Linear Regression also provides a more interpretable model for the finance team.

The model coefficients represent predictive associations and should not be interpreted as causal effects.

## Files

- `milestone-1-customer-spend.csv` — customer dataset
- `UrbanCart_Milestone_1_Solution.ipynb` — analysis, modeling and evaluation
- `README.md` — project documentation
=======
# UrbanCart-Milestone-1
UrbanCart customer spend prediction — Milestone 1 machine learning assignment.
>>>>>>> 498026bbaa106a7876c2104b0da7cf7a5e0d5e60
