# Heart Attack Risk Predictor

## Overview
This project aims to develop an application that predicts the risk of a heart attack in individuals. By leveraging various machine learning algorithms and the AutoML library EvalML, we will identify the best predictive model. The project involves several steps including data analysis, feature engineering, standardization, model building, and predictions.

## Table of Contents
- [Introduction](#introduction)
- [Features](#Key-Features)
- [Project Structure](#project-structure)

## Introduction
Cardiovascular diseases, including heart attacks, are leading causes of mortality worldwide. Early prediction and intervention can save lives. This project utilizes machine learning techniques to predict heart attack risks based on various health indicators and features extracted from the dataset.


## Key Features
- **Data Preprocessing:** Handling missing values, outliers, and categorical variables.
- **Feature Engineering:** Creation of interaction terms and polynomial features to capture complex relationships.
- **Model Development:** Implemented and compared various machine learning algorithms, including:
  - Logistic Regression
  - Decision Trees
  - Random Forests
  - K-Nearest Neighbors (KNN)
  - Support Vector Machines (SVM)
- **Model Evaluation:** Achieved **92% accuracy** and **88.5% AUC score** using the Random Forest model.
- **Feature Importance Analysis:** Identified key predictors like age, cholesterol levels, and blood pressure.


## Project Structure
```
heart-attack-risk-predictor/
│
├── data/
│   └── dataset.csv
├── Heart_Attack_Risk_Predictor_with_EvalML.ipynb
├── README.md
└── requirements.txt
```


