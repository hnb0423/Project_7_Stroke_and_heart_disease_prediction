# Project_7_Stroke_and_heart_disease_prediction

## Business problem
The goal of this project is to predict whether a person will be a victim of stroke or heart disease. 

## Raw Data
Stroke Dataset: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset <br/>
Heart Disease Dataset: https://www.kaggle.com/dileep070/heart-disease-prediction-using-logistic-regression

## Data Processing:
Plot distribution of non-null values by columns. Impute numeric missing values with either mean or median. Replace categorical missing values with the most frequent categories in columns. 

## EDA
Compute a series of plots, including pie charts, bar charts, line charts, and correlation matrix plot. Generate useful insights from data. 

## Feature engineering:
Encode categorical variables. Utilize SMOTE resampling method to resolve the issue of imbalanced response variables in both datasets. Since there is issue of multicollinearity in heart disease dataset, I decide to apply principal component analysis (PCA)for demision reduction. Then I select important variables based on PCA components. 

## Models Construction and Evaluation:
Apply decision tree random forest, logistic regression, and GRNN nerual network to training dataset. Plot confusion matrix and ROC curves. For stroke dataset, random forest has the highest accuracy, and for heart disease dataset, GRNN nerual network performs the best.
