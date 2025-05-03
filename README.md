# 👩‍💼 Workforce Retention Forecast

## 📌 Overview

This project presents a detailed analysis of employee churn using machine learning—specifically, the **Classification and Regression Trees (CART)** algorithm. It aims to help organizations predict which employees are likely to resign, uncover the drivers behind dissatisfaction, and shape better retention strategies.

## 🎯 Motivation

In high-growth and evolving organizations, workforce stability is a critical asset. This project stems from the need to:

* Prevent burnout by defining working condition thresholds
* Assign projects aligned with employee strengths
* Launch initiatives aligned with career goals
* Identify hidden high performers and sources of churn

By leveraging HR analytics and predictive modeling, companies can proactively enhance job satisfaction, reduce turnover, and retain key talent.

## 📂 Project Components

### 1. 🔍 Business Case Definition

Formulated a clear business objective to predict employee churn and visualize the attributes that influence satisfaction and loyalty.

### 2. 📊 Data Exploration & Preparation

Used a simulated HR dataset with both continuous and categorical features:

* Satisfaction level
* Last evaluation
* Number of projects
* Average monthly hours
* Time at the company
* Work accident indicator
* Promotions in the last 5 years
* Salary grade
* Department

### 3. 🧹 Data Visualization

Analyzed the distribution of churn across different salary grades, departments, and workload variables using bar plots, density plots, and correlation heatmaps.

### 4. 🤖 Predictive Modeling

Applied the **CART algorithm** to categorize loyalty and predict likelihood of resignation. Evaluated model accuracy using training-validation split and interpreted decision paths.

## 🧪 How to Use

Open and run the Jupyter notebook in this repository to follow the complete churn prediction pipeline, including data visualization, model training, and evaluation.

> 📓 [Click here to access the notebook](./Workforce_Churn_Cart_Model.ipynb)

## 🗂️ Data Dictionary

| Feature                  | Description                                            |
| ------------------------ | ------------------------------------------------------ |
| `satisfaction_level`     | Employee’s job satisfaction rating                     |
| `last_evaluation`        | Most recent performance evaluation score (0–1 scale)   |
| `number_projects`        | Number of projects assigned to the employee            |
| `average_monthly_hours`  | Monthly average office hours                           |
| `time_spent_company`     | Years spent at the company                             |
| `work_accident`          | Whether the employee had a workplace accident (0 or 1) |
| `promotion_last_5_years` | Whether the employee was promoted in the last 5 years  |
| `resigned`               | Binary flag indicating resignation (1) or active (0)   |
| `salary_grade`           | Salary level (e.g., low, medium, high)                 |
| `department`             | Department to which the employee belongs               |

