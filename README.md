# Titanic - Machine Learning from Disaster

A beginner-level machine learning project built on the classic Kaggle Titanic dataset, predicting passenger survival based on features like class, sex, age, and fare.

## Overview
This project follows the core ML workflow: data exploration, cleaning, feature preparation, model training, and evaluation. The goal was to build a solid, understandable baseline model rather than optimize for the highest possible score.

## Steps Followed
- Loaded and explored the dataset (`.head()`, `.info()`, `.describe()`, missing value checks)
- Performed basic EDA with visualizations (survival by sex, class, age distribution)
- Handled missing values (median for Age/Fare, mode for Embarked, dropped Cabin)
- Selected features: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`
- Encoded categorical columns (Sex, Embarked) into numeric form
- Trained and compared two models: Logistic Regression and Random Forest
- Selected the better-performing model based on validation accuracy
- Generated predictions and created `submission.csv`

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Result
Kaggle Public Leaderboard Score: **0.75598**

## Notebook
See `titanic_notebook.ipynb` for the full code and explanations.
