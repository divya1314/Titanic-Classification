# Titanic Classification Project

## Project Overview

The Titanic Classification Project aims to build a predictive model to determine the likelihood of survival for passengers on the Titanic using data science techniques in Python. This project involves data preprocessing, feature engineering, model training, evaluation, and visualization to gain insights into the factors influencing survival.

## Dataset

The dataset used for this project is the Titanic dataset, which can be found [here](Titanic Dataset). The dataset contains information about the passengers such as age, sex, passenger class, fare, and whether they survived.

## Project Steps

### Data Loading and Exploration:

The dataset is loaded and explored to understand the structure, data types, and missing values.

### Data Preprocessing:

- Handling missing values by imputing median age and mode of embarked.
- Extracting titles from passenger names and creating new feature 'Title'.
- Converting categorical variables into dummy/indicator variables.
- Dropping unnecessary columns.

### Feature Scaling:

Features are scaled using StandardScaler to standardize the data.

### Model Training:

Two machine learning models are trained:
- Logistic Regression
- Random Forest Classifier

### Model Evaluation:

Models are evaluated using accuracy score, confusion matrix, and classification report to determine their performance.

### Visualization:

Various visualizations are created to understand the data distribution and the relationship between different features and survival rates.

## Results

- Logistic Regression Accuracy: 83%
- Random Forest Classifier Accuracy: 84%
- Number of survivors: 342
- Number of non-survivors: 549

## Visualizations

- Distribution of Survival
- Survival Rate by Passenger Class
- Survival Rate by Sex
- Age Distribution by Survival
- Fare Distribution by Survival
- Correlation Matrix Heatmap
- Survival Rate by Embarked
- Survival Rate by Title

## Conclusion

This project demonstrates the use of data science techniques to predict the likelihood of survival of Titanic passengers. By preprocessing the data, engineering relevant features, and applying machine learning models, we gain insights into the factors affecting survival and achieve a predictive accuracy of 84% with the Random Forest Classifier.
