# Mean Salary Prediction

## Introduction

This project is about prediction of mean salary for each vacancy response. The goal was to solve the regression task of minimizing error of salary prediction. The solution leverages machine learning techniques, specifically gradient boosting models, to analyze various job features, criterias for candidates and provide accurate salary estimates.

## Datasets

The project used two main datasets:

`train_contest.csv`: Training data containing job vacancy information and corresponding mean salaries;
`for_prediction.csv`: Test data for making salary predictions.

Datasets included vacancies information from HeadHunter and were gor by HH API.

Key features used in the model include:

*    Job name/title;
*    Region/area;
*    Address;
*    Employer information;
*    Job description;
*    Work schedule;
*    Required key skills;
*    Required experience level;
*    Specializations.

## Used Tools & Libraries

The implementation utilizes the following Python libraries:

*    `CatBoost`: Gradient boosting library for regression tasks;
*    `Pandas` & `NumPy`: Data manipulation and numerical operations;
*    `Scikit-learn`: Model evaluation and preprocessing;
*    `Optuna`: Hyperparameter optimization;
*    `Matplotlib` & `Seaborn`: Data visualization;
*    `OrdinalEncoder` & `RobustScaler`: Feature preprocessing.

## Results

According to **MAE** quality metric usage, my team stroke the score of about 29000 which is, probably, not the best option in real life, but we were on the 3rd place of educational Kaggle contest.

For contest extra info press [here](https://kaggle.com/competitions/ensembles-competition).

## Perspectives of Usage

This project idea can be used in almost any company which is interested in automatization of employees' analyzing in aspect of salary. Of course, there're some troubles which should be fixed and redone, but this project has really huge perspectives with integration of newest ways of language processing or other ways for feature extraction and preprocessing.
