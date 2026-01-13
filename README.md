# Week 3 – Linear Regression From Scratch

This repository contains my Week 3 assessment for Machine Learning.

## Contents
- linear_regression_scratch.ipynb  
  Implementation of Linear Regression from scratch using NumPy.

- analysis_notes.txt  
  Explanation of loss behavior, learning rate experiments, and thinking tasks.

## Dataset
Salary Dataset (YearsExperience vs Salary)

## Tools Used
- Python
- NumPy
- Pandas
- Matplotlib

## Note
sklearn is used only for final comparison as allowed.

TASK 1: DATA UNDERSTANDING
Q1. Why is this dataset suitable for Linear Regression?

This dataset is suitable for Linear Regression because it has one input and one output.
Salary increases as years of experience increase, showing a linear trend.
Since salary is a continuous value, Linear Regression is appropriate.

Q2. What assumption does Linear Regression make?

Linear Regression assumes that the relationship between input and output is linear.
This means changes in input cause proportional changes in output.

TASK 5: COMPARISON WITH SKLEARN

Q1. Why values are similar but not identical?

Values are similar because both models learn the same relationship.
Small differences occur due to optimization methods and precision.

Q2. What sklearn does differently?

sklearn uses optimized algorithms and internal checks for faster and stable training


