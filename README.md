Medical Charges Prediction -Linear Regression Model
Project Overview
This project builds and evaluates a Linear Regression model to predict individual medical insurance charges. Using a dataset of 1,337 patients, the model identifies how demographic and lifestyle factors — age, BMI, smoking status, and region — drive healthcare costs.
Dataset
Source: insurance.csv  |  1,338 rows, 7 columns, no missing values
Cleaned_insurance.csv| 1,337 rows and 7 columns 
 Methodology
 Cleaned the data , removed duplicates 
•	Encoded categorical features using one-hot encoding (sex, smoker, region).
•	Split data 80/20 into training and test sets (random_state=42).
•	Standardised features with StandardScaler before model fitting.
•	Trained a Linear Regression model using scikit-learn.
•	Evaluated on the held-out test set and validated with 5-fold cross-validation.
Dependencies
Python 3 · pandas · numpy · scikit-learn · matplotlib · seaborn
