# Diabetes Prediction using Machine Learning

## Overview

This repository contains a Jupyter Notebook (`diabetes.ipynb`) that demonstrates the process of developing a machine learning model for predicting whether people have diabetes based on their characteristics.

## Dataset

The dataset used in this project is stored in `diabetes.csv`. It contains various features, including age, BMI, insulin level, blood pressure, pregnancies, and more. The target variable is the "Outcome" column, which indicates whether a person has diabetes (1) or not (0).

## Dependencies

Make sure you have the following Python libraries installed to run the code:

- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn


## Data Preprocessing

The Jupyter Notebook begins by loading the dataset and performing data preprocessing steps such as handling missing values, outlier analysis, and creating new variables like age groups, BMI categories, insulin levels, and blood pressure categories.

## Exploratory Data Analysis (EDA)

After preprocessing the data, EDA is performed to gain insights into the data distribution, correlation between features, and other statistical summaries. The Jupyter Notebook includes various visualizations, such as histograms and a correlation matrix heatmap.

## Feature Engineering

The notebook demonstrates how to encode categorical variables using label encoding and one-hot encoding. It also standardizes numerical features using the StandardScaler from scikit-learn.

## Model Building

Two machine learning models are built for diabetes prediction:

1. Random Forest Classifier: This model uses the RandomForestClassifier from scikit-learn to predict the outcome based on the selected features.

2. K-Nearest Neighbors Classifier (KNN): The KNN model is implemented using the KNeighborsClassifier from scikit-learn.

## Model Evaluation

The performance of both models is evaluated using various metrics, including accuracy, precision, recall, F1-score, and ROC-AUC score. Cross-validation is used to obtain more reliable estimates of model performance.

## Hyperparameter Tuning

For the KNN model, hyperparameter tuning is performed using GridSearchCV from scikit-learn to find the optimal number of neighbors (n_neighbors).

## Conclusion

The notebook concludes with the best-performing model and provides instructions for saving and deploying the model for future use.

Feel free to explore the `diabetes.ipynb` notebook for a detailed understanding of the data analysis and machine learning process for diabetes prediction.
