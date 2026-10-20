# Boston Housing Regression Lab

## Overview

This project explores the Boston Housing dataset using Ridge Regression to predict median home values (MEDV).

## Objectives

- Perform exploratory data analysis
- Create a correlation matrix
- Train a Ridge Regression model
- Evaluate model performance using:
  - R²
  - MSE
  - MAE
- Test feature scaling
- Test polynomial feature expansion
- Compare model performance

## Results

| Model | Test Score |
|---------|---------|
| Ridge Regression | 0.703 |
| Scaled Ridge Regression | 0.689 |
| Polynomial Ridge Regression | 0.795 |

## Conclusion

The Polynomial Ridge model achieved the best performance with a test score of approximately 0.795. Feature scaling had minimal impact on model performance.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook