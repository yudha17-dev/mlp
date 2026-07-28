# Titanic Survival Prediction

## Overview
This project predicts passenger survival on the Titanic using the classic Kaggle Titanic dataset. 
Given passenger attributes such as age, sex, ticket class, and family size, the goal is to build 
a binary classification model that predicts whether a passenger survived (1) or did not survive (0).

This was built as part of a series of daily machine learning projects, focused on practicing the 
full ML workflow: data cleaning, feature engineering, model training, validation, and evaluation.
## Dataset
Source: Kaggle
Dataset: Titanic

| Variable | Definition | Key |
|---|---|---|
| survival | Survival | 0 = No, 1 = Yes |
| pclass | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd |
| sex | Sex | |
| Age | Age in years | |
| sibsp | # of siblings / spouses aboard the Titanic | |
| parch | # of parents / children aboard the Titanic | |
| ticket | Ticket number | |
| fare | Passenger fare | |
| cabin | Cabin number | |
| embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton |

## Results
Results were evaluated on the Kaggle website through submission
The following results use a dataset that was not feature engineered (coming soon)
| Model | Accuracy |
|---|---|
| Logistic Regression | 0.753 |
| Random Forest | 0.753 |
| XGBoost | 0.753 |
