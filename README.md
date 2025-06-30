# Titanic EDA Project

This repository contains an **Exploratory Data Analysis (EDA)** performed on the Titanic dataset (`tested.csv`). The goal is to analyze the data visually and statistically to uncover patterns, trends, and relationships that influenced survival.

## Files Included
`tested.csv`        --   Titanic test dataset used for analysis               
`eda_tested.ipynb`  --   Jupyter Notebook containing all EDA steps and plots  
`report.pdf`        --   PDF version summarizing the key findings         

## Task Objective

To perform a thorough Exploratory Data Analysis using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**, and:
- Understand data structure
- Visualize distributions and relationships
- Detect missing values and outliers
- Identify patterns affecting survival

## Tools & Libraries Used

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## Summary of Findings

- Most passengers were from **Pclass 3** and embarked from **Southampton (S)**.
- Majority of passengers were **male**, and survival was higher among **females**.
- **Fare** had a large range and strong positive correlation with **survival**.
- **1st class passengers** had significantly better survival chances.
- There are missing values in `Age`, `Cabin`, and `Embarked` which need to be addressed in modeling.

