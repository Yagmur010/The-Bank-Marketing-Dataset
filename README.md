# STAT 412 Interim Report – Bank Marketing Project

## 📌 Project Overview

This project is part of the STAT 412 course and involves exploratory and predictive analysis of the Bank Marketing dataset obtained from the UCI Machine Learning Repository. The main goal is to analyze factors that influence whether a client will subscribe to a term deposit and to build a logistic regression model for prediction.

---


## 📊 Dataset Description

The dataset includes information from a Portuguese banking institution's marketing campaigns. Each row represents a client, and the target variable is:

- `y`: Whether the client subscribed to a term deposit (`yes` or `no`)

The dataset contains both numerical and categorical features such as:
- `age`, `job`, `marital`, `education`, `default`, `housing`, `loan`, `contact`, `month`, `day_of_week`, `duration`, `campaign`, `pdays`, `previous`, and `poutcome`.

---

## 🧪 Methods and Tools

- Data Cleaning and Transformation
- Exploratory Data Analysis (EDA)
- Handling Missing Values
- Feature Engineering
- Logistic Regression Modeling
- Multicollinearity Check (VIF)
- Evaluation using Accuracy and Confusion Matrix

Libraries used:
```r
dplyr, ggplot2, skimr, naniar, car, DataExplorer


