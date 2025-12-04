# OLA-Driver-Churn-Prediction-Using-Ensemble-Models

## Problem Statement

Ola faces a high churn rate among its drivers, which increases acquisition costs and affects operational stability. Retaining existing drivers is far more economical than recruiting new ones.
This project predicts whether a driver will churn using demographic, performance, and financial attributes.

## Objectives

* Predict whether a driver will churn in upcoming months.
* Identify the most influential factors contributing to attrition.
* Compare Bagging vs Boosting performance.
* Provide actionable business insights for driver retention.

## Models Used

## Bagging
* Random Forest Classifier
## Boosting
* Gradient Boosting Classifier
* XGBoost Classifier

## Dataset:


| Column Name              | Description                                                              |
|--------------------------|--------------------------------------------------------------------------|
| MMM-YY                   | Reporting month (e.g., Jan-20, Feb-20)                                   |
| Driver_ID                | Unique identifier for each driver                                        |
| Age                      | Age of the driver                                                        |
| Gender                   | Driver gender (Male = 0, Female = 1)                                     |
| City                     | City code where the driver operates                                      |
| Education_Level          | Education level (0 = 10+, 1 = 12+, 2 = Graduate)                         |
| Income                   | Average monthly income of the driver                                     |
| Date Of Joining          | Date when the driver joined the platform                                 |
| LastWorkingDate          | Driver’s last working date (null if still active)                        |
| Joining Designation      | Driver’s designation at the time of joining                              |
| Grade                    | Driver’s grade at reporting time                                         |
| Total Business Value     | Monthly business value (negative = cancellations/refunds/EMI adjustments)|
| Quarterly Rating         | Driver’s quarterly rating (1–5; higher is better)                        |
