# Titanic Survival Prediction

A machine learning classification project based on the Titanic dataset.

This is one of my first end-to-end machine learning projects. The goal was to build a model that predicts whether a passenger survived the Titanic disaster and to learn the main steps of a machine learning workflow.

## Project Overview

The project covers the complete ML pipeline:

* Exploratory Data Analysis (EDA)
* Data cleaning
* Handling missing values
* Feature engineering
* Encoding categorical variables
* Feature scaling
* Model training
* Cross-validation
* Model comparison
* Hyperparameter tuning
* Final prediction and Kaggle submission

## Dataset

The project uses the Titanic dataset provided by Kaggle.

The target variable is:

* `Survived = 1` — passenger survived
* `Survived = 0` — passenger did not survive

The dataset contains information about passengers such as:

* Passenger class
* Sex
* Age
* Number of siblings/spouses
* Number of parents/children
* Ticket
* Fare
* Cabin
* Port of embarkation

## Feature Engineering

Several features were created or transformed to improve the information available to the models.

Examples include:

* `cabin_multiple`
* `cabin_adv`
* `numeric_ticket`
* `ticket_letters`
* `name_title`

Categorical variables were encoded before training the models, and numerical features were processed where appropriate.

## Machine Learning Models

Several classification algorithms were tested:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* XGBoost
* Naive Bayes

The models were compared using cross-validation rather than relying only on a single train/test split.

## Model Tuning

After comparing the initial models, hyperparameter tuning was performed using `GridSearchCV`.

The goal was to test different combinations of model hyperparameters and evaluate them using cross-validation.

For example, parameters such as regularization strength, tree depth, number of estimators, and other model-specific parameters were tested depending on the algorithm.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

## What I Learned

This project helped me understand the structure of an end-to-end machine learning workflow.

In particular, I practiced:

* exploring and understanding a dataset;
* identifying and handling missing data;
* creating useful features;
* preparing data for machine learning models;
* training and comparing different classification algorithms;
* using cross-validation;
* understanding the purpose of hyperparameters;
* using `GridSearchCV` for hyperparameter tuning.

I am continuing to study the underlying mechanics and mathematics of the machine learning algorithms used in this project.
```

## Future Improvements

As I continue learning machine learning, I plan to revisit this project and improve:

* feature engineering;
* model interpretation;
* hyperparameter tuning;
* model evaluation;
* understanding of the algorithms behind the models.
