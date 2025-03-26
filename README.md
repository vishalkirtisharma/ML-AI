# Project Documentation

## Introduction
This project implements various machine learning models to predict outcomes based on input features. The first model implemented is a simple linear regression model that predicts salaries based on years of experience.

## Simple Linear Regression
The simple linear regression model predicts salaries based on the number of years of experience. It utilizes a dataset containing salary information and applies linear regression techniques to establish a relationship between experience and salary.

## Multiple Linear Regression
The multiple linear regression model predicts outcomes based on multiple input features. It extends the simple linear regression model by allowing for more than one independent variable. This model is useful for understanding the relationship between several predictors and a response variable.

The dataset used for this model is `50_Startups.csv`, which contains information about various startups and their respective features.

## Polynomial Regression
Polynomial regression is a form of regression analysis in which the relationship between the independent variable \(x\) and the dependent variable \(y\) is modeled as an \(n\)th degree polynomial. This model is useful for capturing non-linear relationships in the data.

In this project, polynomial regression is implemented to predict salaries based on position levels. The dataset used for this model is `Position_Salaries.csv`, which contains information about various positions and their corresponding salaries.

Polynomial regression can provide a better fit for the data compared to simple linear regression when the relationship is not linear.

## Support Vector Regression
The Support Vector Regression (SVR) model is implemented to predict salaries based on position levels. It utilizes the dataset `Position_Salaries.csv` and applies the SVR technique to capture the relationship between position levels and salaries.

For detailed implementation and results, please refer to the [Support Vector Regression documentation](04) Support Vector Regression/support_vector_regression_documentation.md).

## Decision Tree Regression
Decision tree regression is a non-parametric supervised learning method used for regression tasks. It models the relationship between features and target values by creating a tree-like structure. The model splits the data into subsets based on feature values, making predictions based on the average target value in each subset.

The dataset used for this model is `Position_Salaries.csv`, which contains information about various positions and their corresponding salaries.

## Future Additions



This section will be updated with additional models and functionalities as the project expands. Future models may include decision trees and more.
