# IBM HR Analytics Employee Attrition & Performance

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#eda)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Deployment](#deployment)
- [Contributing](#contributing)

## Overview

This Data Science project focuses on predicting employee attrition using the IBM HR Analytics Employee Attrition & Performance dataset. Employee attrition can have a significant impact on an organization's productivity and bottom line. By developing predictive models, we aim to identify factors contributing to attrition and provide actionable insights to HR professionals.

## Dataset

The dataset contains 1470 records and 35 columns, including both numerical and categorical features. Key columns include "Age," "BusinessTravel," "DistanceFromHome," and "Attrition" (the target variable). The dataset was sourced from [https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset?datasetId=1067&sortBy=voteCount].

## Exploratory Data Analysis (EDA)

During the EDA phase, we thoroughly explored the dataset to gain insights into employee attrition trends. We conducted various visualizations to understand the distribution of variables, identify correlations, and pinpoint potential influential factors.

## Data Preprocessing

Data preprocessing was a critical step in preparing the dataset for modeling. We addressed missing values, converted categorical variables into a suitable format, and eliminated irrelevant or redundant columns. The preprocessing pipeline included [mention specific preprocessing steps].

## Modeling

We employed several classification models to predict employee attrition. The models tested include:
- Logistic Regression
- Random Forest
- Decision Tree
- K-Nearest Neighbors

For each model, we utilized cross-validation and hyperparameter tuning to optimize performance. We also experimented with resampling techniques to handle class imbalance.

## Evaluation

Model evaluation was based on accuracy, precision, recall, and F1-score. The model that achieved the highest accuracy on the test dataset was Logistic Regression with accuracy 89.67 .

## Deployment

The models can be deployed for real-time predictions in an HR analytics platform or integrated into an HR management system to proactively identify attrition risks and take preventive actions.

## Contributing

Contributions to this project are welcome. If you have any suggestions, improvements, or would like to report issues, please feel free to create a pull request or open an issue.


