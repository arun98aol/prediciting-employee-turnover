## Predicting Employee Turnover with Machine Learning
---

## Table of Contents

1. [Introduction](#introduction)
2. [Data Collection and Preprocessing](#data-collection-and-preprocessing)
3. [Feature Engineering](#feature-engineering)
4. [Methods](#methods) ([Orange-Workflows folder](https://github.com/arun98aol/prediciting-employee-turnover/tree/main/orange-workflows))
5. [Final Model Selection](#final-model-selection)
6. [Evaluation Metrics](#evaluation-metrics)
7. [Conclusion](#conclusion)

---

## Introduction

Employee turnover is a critical challenge that businesses face, leading to increased costs and decreased morale. This project uses data science and machine learning to predict employee turnover, aiding organizations in implementing effective retention strategies.

## Data Collection and Preprocessing

We collected a dataset of 14,999 observations with 8 features from Kaggle. The dataset was split into training and future prediction sets. Preprocessing included random separation and normalization.

## Feature Engineering

Features include self-reported employee satisfaction, project count, average monthly hours, tenure, work accident history, promotions, department, and salary. The target variable is employee churn (left job or stayed).

## Methods [orange-workflows](https://github.com/arun98aol/prediciting-employee-turnover/tree/main/orange-workflows)

Several machine learning models were explored: Logistic Regression, KNN, Single Decision Tree, Random Forest, Gradient Boosting, Neural Networks, and SVM. Random Forest emerged as the best-performing model based on AUC.

## Final Model Selection

Random Forest with an AUC of 0.992 was selected as the final model for predicting employee turnover.

## Evaluation Metrics

Evaluation included Confusion Matrix, ROC Curve, Lift Curve, and Profit/Cost Analysis to maximize expected profit from retention strategies.

## Conclusion

This project demonstrates the efficacy of using machine learning to predict employee turnover and offers insights into designing retention strategies for businesses.

---

_For detailed figures, tables, and full content, please refer to the complete [report](https://github.com/arun98aol/prediciting-employee-turnover/blob/main/Employee_Churn_Report.pdf)._
