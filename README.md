# KNN Regression on Car Dataset

## Project Overview

This project implements a complete K-Nearest Neighbors (KNN) regression pipeline on a car dataset to predict the **miles per gallon (mpg)** of cars based on their features. 
The pipeline includes data cleaning, scaling, stratified k-fold cross-validation, and performance evaluation.

## Objectives (Based on Meeting Notes)

* Read and clean the data (`car.csv`)
* Perform train-test split
* Apply feature scaling
* Implement a suitable regression model

##  Dataset

* **File**: `cars.csv`
* **Target Variable**: `mpg` 
* **Features**: Various car attributes 

Cleaning performed:

* Dropped the `Unnamed: 0` column, which contains car names and is not required for modeling.


##  Steps Executed

1. Data loading and preprocessing
2. Binning of target variable for stratification
3. KNN pipeline setup with scaling
4. Stratified 5-fold cross-validation using `cross_val_score`
5. Final training on train set and evaluation on test set

###  Evaluation Metrics:

* `R² Score` for cross-validation
