# Data Science Final Project Report

## Predicting Employee Turnover with Machine Learning

**Authors:** Arun Ganapathy, Skyler Schneekloth, Cynthia I Ibeawuchi, Jacqlyn Caspers  
**Date:** April 22nd, 2023

---

## Table of Contents

1. [Introduction](#introduction)
2. [Data Collection and Preprocessing](#data-collection-and-preprocessing)
3. [Feature Engineering](#feature-engineering)
4. [Methods](#methods)
    - [Logistic Regression](#logistic-regression)
    - [K-Nearest Neighbors (KNN)](#k-nearest-neighbors-knn)
    - [Single Decision Tree](#single-decision-tree)
    - [Random Forest](#random-forest)
    - [Gradient Boosting](#gradient-boosting)
    - [Neural Networks](#neural-networks)
    - [Support Vector Machine (SVM)](#support-vector-machine-svm)
5. [Final Model Selection](#final-model-selection)
6. [Evaluation Metrics](#evaluation-metrics)
    - [Confusion Matrix](#confusion-matrix)
    - [ROC Curve](#roc-curve)
    - [Lift Curve](#lift-curve)
    - [Profit/Cost Analysis](#profitcost-analysis)
7. [Conclusion](#conclusion)
8. [References](#references)
9. [Appendix](#appendix)

---

## Introduction

Employee turnover is a critical challenge that businesses face, leading to increased costs and decreased morale. This project uses data science and machine learning to predict employee turnover, aiding organizations in implementing effective retention strategies.

## Data Collection and Preprocessing

We collected a dataset of 14,999 observations with 8 features from Kaggle. The dataset was split into training and future prediction sets. Preprocessing included random separation and normalization.

## Feature Engineering

Features include self-reported employee satisfaction, project count, average monthly hours, tenure, work accident history, promotions, department, and salary. The target variable is employee churn (left job or stayed).

## Methods

Several machine learning models were explored: Logistic Regression, KNN, Single Decision Tree, Random Forest, Gradient Boosting, Neural Networks, and SVM. Random Forest emerged as the best-performing model based on AUC.

## Final Model Selection

Random Forest with an AUC of 0.992 was selected as the final model for predicting employee turnover.

## Evaluation Metrics

Evaluation included Confusion Matrix, ROC Curve, Lift Curve, and Profit/Cost Analysis to maximize expected profit from retention strategies.

## Conclusion

This project demonstrates the efficacy of using machine learning to predict employee turnover and offers insights into designing retention strategies for businesses.

---

_For detailed figures, tables, and full content, please refer to the complete report._
