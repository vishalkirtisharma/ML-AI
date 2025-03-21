# Polynomial Regression Documentation

## Overview
Polynomial Regression is a form of regression analysis in which the relationship between the independent variable (X) and the dependent variable (Y) is modeled as an nth degree polynomial. This technique is useful when the data shows a curvilinear relationship.

## Purpose
The purpose of this notebook is to demonstrate how to implement Polynomial Regression to predict salaries based on position levels. It compares the performance of a linear regression model with a polynomial regression model.

## Methodology
1. **Data Import**: The dataset `Position_Salaries.csv` is imported, which contains information about various positions and their corresponding salaries.
2. **Data Exploration**: The notebook performs initial data exploration, including checking for duplicates and null values, and visualizing the salary data.
3. **Model Training**:
   - A linear regression model is trained on the data.
   - A polynomial regression model is created by transforming the input features into polynomial features of degree 4.
4. **Visualization**: The results of both models are visualized to compare their performance.
5. **Predictions**: Predictions are made for a specific position level (6.5) using both models.

## Conclusion
Polynomial Regression provides a better fit for the data compared to linear regression when the relationship between the variables is non-linear. This notebook illustrates the implementation and comparison of both models.

## Future Work
Future enhancements may include experimenting with different polynomial degrees, evaluating model performance using cross-validation, and exploring other regression techniques.
