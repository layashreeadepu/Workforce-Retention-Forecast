# Workforce Retention Forecast

## Overview

This GitHub repository contains a comprehensive analysis of employee churn rate prediction using data science techniques, specifically the Classification and Regression Trees (CART) algorithm. The project aims to help organizations identify potential employee resignations, understand the factors influencing loyalty or dissatisfaction, and ultimately improve retention strategies.

## Introduction

In today's dynamic work environment, understanding and predicting employee churn is crucial for maintaining a healthy and productive workforce. This project explores the application of HR analytics and machine learning to predict employee churn rates, providing actionable insights for businesses.

## HR Analytics and Churn Rate Prediction

HR analytics involves collecting and analyzing employee data to gain insights into workforce trends. Predicting employee churn rates is essential for:

1. Generalizing standards for working conditions to avoid burnout.
2. Assigning projects aligned with employees' strengths for better performance.
3. Launching initiatives that align with career aspirations for higher satisfaction.
4. Evaluating performance to uncover sources of talent.

By utilizing data-driven approaches, organizations can retain talented employees, enhance job satisfaction, foster company loyalty, and reduce hiring and retention costs.

## Churn Rate Prediction Using CART Algorithm

The Classification and Regression Trees (CART) algorithm is employed to categorize loyalty and identify employees likely to resign. This analysis goes beyond predicting churn rates; it aims to identify the factors contributing to employee dissatisfaction or loyalty.

### Steps in the Analysis

1. **Business Case**: Formulating the business case around predicting employee churn and visualizing the attributes influencing loyalty and dissatisfaction.

2. **Data Exploration and Preparation**: Exploring a simulated dataset containing various measures to predict employee churn. The data includes continuous and categorical variables such as satisfaction level, last evaluation, number of projects, average monthly hours, time spent in the company, work accidents, promotions, salary grade, and department.

3. **Data Visualization**: Plotting key variables to better understand the distribution of employees across departments, salary grades, and the number of resignations.

4. **Splitting Data into Training and Validation Sets**: Understanding the importance of training and validation sets in machine learning. The dataset is split to train the algorithm and evaluate its performance on a representative dataset.

## How to Use

Follow the steps outlined in the Jupyter notebook provided in this repository to perform the analysis on your own machine. Click [here](link-to-notebook) to access the notebook.

## Data Dictionary

1. `satisfaction_level`: Satisfaction ratings of an employee's job.
2. `last_evaluation`: Rating received by an employee over their job performance during the last evaluation (scale 0 to 1).
3. `number_projects`: Number of projects an employee is involved in.
4. `average_monthly_hours`: Average number of hours spent by an employee at the office per month.
5. `time_spent_company`: Number of years an employee has spent in the company.
6. `work_accident`: Binary indicator (0 or 1) representing whether there was an accident during the employee's stay.
7. `promotion_last_5_years`: Number of promotions an employee received in the last 5 years.
8. `resigned`: Binary indicator (0 or 1) representing whether the employee resigned from the company.
9. `salary_grade`: Salary earned by an employee.
10. `department`: The department to which an employee belongs.

Feel free to explore and modify the notebook to suit your specific requirements. Happy analyzing!
