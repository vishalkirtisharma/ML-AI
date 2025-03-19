# Simple Linear Regression Model Documentation

## Introduction
This Jupyter notebook implements a simple linear regression model to predict salaries based on years of experience. The model is trained on a dataset containing salary information and years of experience.

## Dataset Description
The dataset used in this notebook is `Salary_Data.csv`, which contains the following columns:
- **YearsExperience**: The number of years of experience.
- **Salary**: The corresponding salary for the given years of experience.

## Steps
1. **Importing Libraries**: Necessary libraries such as NumPy, Pandas, Matplotlib, and Seaborn are imported for data manipulation and visualization.
2. **Loading the Dataset**: The dataset is loaded using Pandas and the first few rows are displayed for exploration.
3. **Preparing Features and Target Variables**: The feature matrix (X) and target vector (y) are prepared by separating the independent and dependent variables.
4. **Splitting the Dataset**: The dataset is split into training and testing sets to evaluate the model's performance.
5. **Training the Model**: A linear regression model is created and trained on the training data.
6. **Making Predictions**: Predictions are made on the test data using the trained model.
7. **Calculating Metrics**: Evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) are calculated to assess the model's performance.
8. **Visualizing Results**: The results are visualized using scatter plots to show the relationship between years of experience and salary for both training and test sets.

## Conclusion
The model successfully predicts salaries based on years of experience, and the evaluation metrics provide insights into its performance. The visualizations help in understanding the relationship between the variables.
