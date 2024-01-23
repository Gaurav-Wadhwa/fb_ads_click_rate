# Facebook Ads Click Prediction

## Problem Statement

You have been hired as a consultant to a start-up that is running targeted marketing ads on Facebook. The company wants to analyze customer behavior by predicting which customer clicks on the advertisement. Customer data includes various parameters such as name, email, country, time on Facebook, estimated salary, and the target variable, 'Clicked' (1: customer clicked on Ad, 0: Customer did not click on the Ad).

## Dataset

The dataset is loaded from 'Facebook_Ads_2.csv'. It includes the following columns:

- Name
- Email
- Country
- Time on Facebook
- Estimated Salary
- Clicked (target variable)

## Exploratory Data Analysis (EDA)

Performed exploratory data analysis on the dataset, including visualizations such as histograms and scatterplots.

## Data Preprocessing

Removed unnecessary columns ('Names', 'emails', 'Country') and split the data into training and testing sets. Applied feature scaling using StandardScaler.

## Models Implemented

### 1. Logistic Regression

Trained a logistic regression model using grid search for hyperparameter tuning. Achieved accuracy on the training set.

### 2. K-Nearest Neighbors (KNN)

Utilized KNN for classification, optimizing the number of neighbors through grid search. Evaluated the model's performance.

### 3. Decision Tree

Implemented a decision tree classifier with hyperparameter tuning. Examined the confusion matrix and accuracy.

### 4. Ensemble Models

#### a. Voting Classifier

Combined Logistic Regression, KNN, and Decision Tree into a hard-voting ensemble. Assessed the ensemble's accuracy.

#### b. Random Forest

Constructed a random forest classifier with grid search for optimal hyperparameters. Analyzed the model's accuracy and confusion matrix.

## Model Testing

Evaluated model performance on the test set for each implemented model.

## Results

Generated a summary table showcasing the accuracy of each model on both the training and test sets.

## Conclusion

Based on the analysis, Logistic Regression and K-Nearest Neighbors demonstrated superior performance compared to Decision Tree, Voting Classifier, and Random Forest in predicting customer clicks on Facebook ads.
