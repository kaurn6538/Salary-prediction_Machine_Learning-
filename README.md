## Employee Salary Prediction
This project aims to predict employee salaries based on various features such as age, gender, degree, job title, and years of experience. The dataset used for this analysis is Dataset09-Employee-salary-prediction.csv.

## Table of Contents
-Introduction

Data Preprocessing
Exploratory Data Analysis
Feature Engineering
Model Development
Model Evaluation
Custom Predictions
Results
## Introduction
The goal of this project is to develop a predictive model for employee salaries using linear regression. The steps include data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

## Data Preprocessing
Reading the Data: The dataset is read into a Pandas DataFrame.

Renaming Columns: Columns are renamed for easier access and readability.

Handling Duplicates: Duplicate rows are identified and removed.

Handling Missing Values: Missing values are dropped from the dataset.

## Exploratory Data Analysis
Data Overview: The initial structure and summary statistics of the dataset are examined.

Correlation Analysis: A correlation matrix is generated to understand relationships between numerical features.

Visualizations:
1.Bar charts to show the distribution of degrees and gender among employees.

2.Histograms and box plots to visualize the distribution of age, experience years, and salary.

## Feature Engineering
*    Label Encoding: Categorical features such as gender, degree, and job title are converted into numerical values using label encoding.
*    Feature Scaling: Numerical features (age and experience years) are standardized using StandardScaler to improve model performance.
## Model Development
*    Splitting the Data: The dataset is split into training and testing sets.
*    Training the Model: A linear regression model is trained on the training data.
*    Making Predictions: The trained model is used to predict salaries on the test data.

## Model Evaluation
Evaluation Metrics:
1. R-squared (R²): Measures the proportion of variance in the dependent variable that is predictable from the independent variables.
   
2. Mean Absolute Error (MAE): Measures the average magnitude of the errors in a set of predictions.
   
3. Root Mean Squared Error (RMSE): The square root of the average of squared differences between prediction and actual observation.

## Custom Predictions
Custom predictions are made by inputting specific attributes such as age, gender, degree, job title, and years of experience, and using the trained model to predict the salary.

## Results
Model Performance:

1. The R-squared value indicates the model's accuracy.
   
2. The Mean Absolute Error and Root Mean Squared Error provide insights into the model's prediction errors.
   
3. Correlation Heatmap: A heatmap visualizing the correlation between age, experience years, and salary shows how these features relate to each other.

## Visualizations:
*    Bar charts reveal the distribution of degrees and gender.
*    Histograms and box plots show the distributions of age, experience years, and salary, helping to understand the spread and outliers in the data.
*    This project demonstrates a complete workflow from data preprocessing and exploratory analysis to model development and evaluation, providing a comprehensive approach to predicting employee salaries based on given features.
