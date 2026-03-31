# Regularization Methods
Ridge, LASSO, and Elastic Net regression on the Boston Housing dataset.

## Overview
This project applies regularization techniques to predict median home values in the Boston Housing dataset. The analysis compares Ridge, LASSO, and Elastic Net regression to standard linear regression, using cross-validation to select optimal tuning parameters.

## Dataset
- **Source:** Boston Housing dataset (UCI Machine Learning Repository)
- **Target variable:** Median home value (medv)
- **Key predictors:** 13 features including rooms (rm), lower status population (lstat), crime rate (crim), and others

## Methods
- K-Fold Cross Validation for model selection
- Ridge Regression (L2 penalty)
- LASSO Regression (L1 penalty) for feature selection
- Elastic Net (combined L1/L2 penalty)
- Descriptive statistics and correlation analysis via `psych`

## Key Findings
- Number of rooms (rm) was the strongest positive predictor of home value
- Lower status population percentage (lstat) was the strongest negative predictor
- LASSO effectively identified and removed less important features through coefficient shrinkage

## Tools & Libraries
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=R&logoColor=white)
![glmnet](https://img.shields.io/badge/glmnet-276DC3?style=flat-square&logo=r&logoColor=white)
![caret](https://img.shields.io/badge/caret-276DC3?style=flat-square&logo=r&logoColor=white)
![psych](https://img.shields.io/badge/psych-276DC3?style=flat-square&logo=r&logoColor=white)

## How to Run
1. Clone the repository: `git clone https://github.com/BronsonBagwell/Regularization_Methods.git`
2. Open the HTML file in a browser, or run the R Markdown file in RStudio
3. Required packages: `glmnet`, `caret`, `psych`
