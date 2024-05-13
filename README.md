## Student Performance Indicator - MLOps

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Data Collection](#data-collection)
- [Data Checks](#data-checks)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Pre-Processing](#data-pre-processing)
- [Model Training](#model-training)
- [Choosing the Best Model](#choosing-the-best-model)
- [Conclusion](#conclusion)

## Introduction

Welcome to myMLOPS, a project focused on analyzing student performance indicators using machine learning techniques. In this project, we delve into understanding how various factors such as gender, ethnicity, parental level of education, lunch type, and test preparation courses influence students' test scores.

## Problem Statement

The primary objective of this project is to analyze the relationship between students' test scores and several independent variables like gender, ethnicity, parental education, lunch type, and test preparation course completion.

## Data Collection

We obtained the dataset from Kaggle, specifically from the [Students Performance in Exams dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977). The dataset consists of 1000 rows and 8 columns.

## Data Checks

Before proceeding with analysis, we performed several checks on the dataset, including identifying unique categories in each categorical variable such as gender, race/ethnicity, parental level of education, lunch type, and test preparation course.

## Exploratory Data Analysis

Exploratory data analysis (EDA) was conducted to gain insights into the dataset's characteristics and distributions. Visualizations and summary statistics were utilized to understand the relationships between variables and identify potential patterns.

## Data Pre-Processing

Prior to model training, data pre-processing steps were carried out, including handling categorical variables through one-hot encoding and scaling numerical features using standardization.

## Model Training

We trained various machine learning models to predict students' math scores based on the given features. The models included Linear Regression, Lasso Regression, Ridge Regression, K-Neighbors Regressor, Decision Tree Regressor, Random Forest Regressor, XGBoost Regressor, CatBoost Regressor, and AdaBoost Regressor.

## Choosing the Best Model

After training, each model's performance was evaluated using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2) score. Based on the evaluation, the Ridge Regression model exhibited the highest R2 score of 0.8806, closely followed by Linear Regression with an R2 score of 0.8790.

## Conclusion

In conclusion, the myMLOPS project successfully analyzed student performance indicators and developed predictive models to forecast math scores based on various factors. The Ridge Regression model emerged as the top performer, showcasing the potential of machine learning in educational analytics.
