# Mental Health Prediction Model

## Overview

This project aims to analyze the impact of various factors on mental health, utilizing machine learning techniques to predict stress levels and identify key determinants. The dataset includes information on demographics, academic performance, and mental health conditions.

## Table of Contents

- [Introduction](#introduction)
- [Data Cleaning](#data-cleaning)
- [Data Exploration](#data-exploration)
- [Model Creation](#model-creation)
- [Results](#results)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)

## Introduction

This project explores the relationship between various factors and mental health outcomes. The dataset covers:

- **Gender**
- **Age**
- **University**
- **Degree Level**
- **CGPA**
- **Academic Workload**
- **Financial Concerns**
- **Social Relationships**
- **Stress Level**

The combined data is used to study trends and build predictive models for stress levels and mental health conditions.

## Data Cleaning

To ensure consistency, the data underwent a series of cleaning steps:

1. Renaming columns for uniformity.
2. Handling missing values using appropriate imputation methods.
3. Formatting categorical variables for analysis.

## Data Exploration

After cleaning the data, we calculated basic statistics to understand the average values for stress levels and related factors. Summary statistics helped identify patterns and trends.

- **Average Stress Level**: Calculated across the dataset.
- **Distribution of Demographics**: Breakdown of gender, age, and academic performance.

## Model Creation

A variety of machine learning models were built to predict stress levels, including:

- **Linear Regression**
- **Random Forest Regressor**
- **Support Vector Regression (SVR)**

Both the **statsmodels** and **sklearn** libraries were used for modeling:

- **Statsmodels**: Used for initial exploratory analysis and OLS regression.
- **Sklearn**: Applied for building, training, and evaluating predictive models.

## Results

- **Mean Squared Error**: A measure of how well the models performed in predicting stress levels.
- **Model Coefficients**: The impact of different features on stress levels.
- **Feature Importance**: Ranking of features based on their contribution to model predictions.

## Visualizations

Several visualizations were created to illustrate trends and relationships:

1. **Distribution Plots**: Visualizations showing the distribution of stress levels across demographics.
2. **Correlation Heatmap**: A heatmap highlighting correlations between various features and stress levels.
3. **Box Plots**: Comparisons of stress levels across different categorical variables, such as gender and degree level.

## Conclusion

This project demonstrates the use of machine learning techniques to analyze and predict mental health outcomes based on various factors. The findings provide insights into the key determinants of stress levels and highlight areas for further research and intervention.
