# Diabetes Risk Prediction

This repository contains a predictive analysis project focused on diabetes risk, using the UCI Diabetes dataset.

## Dataset

The UCI Diabetes dataset includes several predictors related to diabetes risk. These predictors include number of pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, DiabetesPedigreeFunction, and age. The goal is to predict the 'Outcome' column, which indicates whether or not a patient has diabetes.

## Data Preprocessing

The data preprocessing phase involved cleaning and filling in missing data. Missing data were detected in some columns (Glucose, BloodPressure, SkinThickness, Insulin, BMI) and were filled with the respective median values.

## Exploratory Data Analysis

The exploratory data analysis phase included identifying and understanding key risk factors for diabetes. The most correlated factors with the outcome were glucose levels, BMI, age, and DiabetesPedigreeFunction.

## Machine Learning Models

Several machine learning models were trained on the preprocessed dataset, including Logistic Regression, Decision Trees, and Random Forests. The performance of these models varied, with an accuracy score up to 75%.

## Handling Class Imbalance

The dataset's class imbalance (unequal representation of classes in the 'Outcome' variable) was addressed using the Synthetic Minority Over-sampling Technique (SMOTE). This improved the performance of the predictive models.

## Hyperparameter Tuning

GridSearchCV was utilized to fine-tune the models, ensuring optimal performance by adjusting hyperparameters.

## Model Evaluation

Various metrics were used to evaluate the performance of the models, including accuracy, confusion matrix, classification report, and the Area Under the Receiver Operating Characteristic Curve (ROC-AUC). The models achieved an ROC-AUC score ranging between 0.72 and 0.73.

## Ensemble Methods

Ensemble methods were implemented to improve model performance, providing more accurate and stable predictions.

## Feature Importance

Feature importance was also calculated, confirming that the most impactful predictors for diabetes are glucose, BMI, Age, and DiabetesPedigreeFunction.

## Conclusion

This project showcases the application of data science methods in healthcare, providing a predictive model for diabetes risk using various patient characteristics. The models created can assist healthcare professionals in identifying high-risk patients, potentially enabling earlier interventions and improved patient outcomes.
