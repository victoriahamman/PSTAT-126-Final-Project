# Diamond Price Regression Analysis

A regression analysis project in **R** that explores which diamond characteristics have the greatest impact on price using statistical modeling and feature selection.

**Author:** Victoria Hamman

## Project Overview

This project analyzes a random sample of 1,000 diamonds to identify the variables that best predict diamond prices. The analysis includes exploratory data analysis, simple and multiple linear regression, model diagnostics, variable transformations, and feature selection.

## Repository Structure

```text
diamond-price-regression/
├── README.md
├── Regression_Analysis.qmd
└── Diamonds Prices2022.csv
```

## Analysis Summary

The project includes:

* Exploratory Data Analysis (EDA)
* Correlation analysis
* Simple linear regression
* Multiple linear regression
* Regression assumption testing
* Log transformations
* AIC model selection
* VIF analysis for multicollinearity

## Results

The final regression model found that **carat, cut, color, and clarity** are the strongest predictors of diamond price. Applying log transformations improved the model fit and satisfied regression assumptions.

## Tools

* R
* dplyr
* GGally
* MASS
* car
