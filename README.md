**Adult Data Logistic Regression Model**

Overview

This repository contains a logistic regression model built on a dataset related to adults. The predictive model is designed to classify whether an adult earns more than $50,000 annually based on various demographic and economic features. The dataset includes columns such as age, workclass, education, marital status, occupation, etc. The logistic regression model is implemented to predict the income category.

Dataset

The dataset used for this project contains information related to adults. It includes features such as age, workclass, final weight, education, education number, marital status, occupation, relationship, race, sex, capital gain, capital loss, hours per week, native country, and income. The target variable is the "income" column, which represents whether an adult earns more than $50,000 annually.

Logistic Regression Model

A logistic regression model has been implemented using the scikit-learn library. Logistic regression is a powerful tool for binary classification tasks, and it is suitable for predicting binary outcomes such as whether an adult's income is above or below a certain threshold. The model has been trained on the dataset, and its performance has been evaluated using appropriate metrics.

Preprocessing Steps

The following preprocessing steps have been performed on the dataset:

Handling categorical variables: Encoding categorical variables like workclass, education, marital status, occupation, relationship, race, sex, and native country using label encoding.

Feature scaling: Standard scaling or normalization of numerical features such as age, capital_gain, capital_loss, and hours_per_week.
