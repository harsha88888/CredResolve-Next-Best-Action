# CredResolve Intelligence Challenge – Next Best Action

Author: Lavanuru Harshavardhan  
Email: harsha200488@gmail.com  
University Email: hlavanur@gitam.in  

## Overview
This repository contains my submission for the CredResolve Intelligence Challenge: "Next Best Action", completed as part of the Data Analyst assignment.

The objective is to predict the probability of successful recovery (TARGET) for a recommended action using borrower metadata and historical patterns.

## Business Problem
Different recovery actions have different costs and effectiveness. The goal is to identify the most suitable next action that maximizes recovery success while minimizing operational cost.

## Dataset Used
- train.csv – training data with target variable
- test.csv – test data for predictions
- metaData.csv – borrower-level metadata

Datasets are merged using the lead_code column.

## Approach
- Data cleaning and merging
- One-hot encoding for categorical features
- Linear Regression model using Scikit-learn Pipeline
- Predictions clipped between 0 and 1

## Model
- Linear Regression (baseline, interpretable model)

## Output
- submission.csv generated in required Kaggle format

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn

## Compliance
- No external data used
- Follows all Kaggle competition rules
- Original, human-written solution

## Author
Lavanuru Harshavardhan  
GITAM University, Bengaluru
