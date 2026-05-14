# Statistical Housing Valuation

### Multiple Linear Regression & Predictive Modeling in R

![R](https://img.shields.io/badge/R-Statistical%20Modeling-blue?style=for-the-badge)
![MLR](https://img.shields.io/badge/Model-Multiple%20Linear%20Regression-orange?style=for-the-badge)
![Feature Engineering](https://img.shields.io/badge/Focus-Feature%20Engineering-green?style=for-the-badge)
![Regression Diagnostics](https://img.shields.io/badge/Method-Regression%20Diagnostics-purple?style=for-the-badge)
![Predictive Analytics](https://img.shields.io/badge/Type-Predictive%20Analytics-red?style=for-the-badge)
![Kaggle](https://img.shields.io/badge/Result-2nd%20Place-gold?style=for-the-badge)

---

## Overview

A statistical modeling and predictive analytics project focused on residential housing valuation using multiple linear regression (MLR), feature engineering, transformation techniques, multicollinearity analysis, and regression diagnostics in R.

The project explores how structural housing characteristics, neighborhood effects, engineered interaction variables, and text-derived review features influence housing sale prices. The final modeling pipeline balances predictive performance with interpretability and statistical validity rather than relying on black-box modeling approaches.

The project achieved **2nd place** on the final Kaggle-style evaluation leaderboard using RMSE-based prediction scoring.

---

## Project Goals

The primary goals of the project were to:

- Build an interpretable statistical model for housing valuation
- Improve predictive performance through feature engineering and transformations
- Reduce multicollinearity using VIF analysis
- Validate regression assumptions using diagnostic analysis
- Compare model complexity versus interpretability
- Evaluate model performance using RMSE-based scoring

---

## Dataset

The dataset contains approximately:

- 7,000 residential housing observations
- 90+ structural, geographic, and engineered variables

The repository includes:

- housing training dataset
- data dictionary
- cleaned analytical workflow
- final modeling report

Key variable categories include:

- structural housing features
- lot and neighborhood characteristics
- quality and condition scores
- garage and basement variables
- temporal housing features
- engineered interaction variables
- text-derived review features

---

## Analytical Workflow

### Data Cleaning & Preparation

- Removed zero-variance and redundant variables
- Standardized categorical and ordinal variables
- Handled missing values and inconsistent feature scales
- Created transformed variables for skewed predictors

### Feature Engineering

Engineered variables included:

- Total housing area variables
- Quality × area interaction features
- House age and remodel age variables
- Garage-related interaction features
- Log-transformed predictors
- NLP-inspired review sentiment features

### Statistical Modeling

The modeling workflow included:

- Multiple linear regression (MLR)
- Log and power transformations
- Backward stepwise regression
- AIC-based model selection
- Variance inflation factor (VIF) analysis
- Residual diagnostics
- Influence and leverage analysis

### Model Diagnostics

The final model was evaluated using:

- residual vs fitted analysis
- QQ plots
- scale-location plots
- leverage analysis
- Cook’s distance
- RMSE evaluation

---

## Key Findings

- Housing sale prices were heavily right-skewed and benefited from log transformation
- Overall housing quality and total living area were among the strongest predictors
- Interaction terms significantly improved explanatory power
- Multicollinearity reduction improved model stability and interpretability
- Engineered features substantially improved predictive performance
- The final model achieved strong adjusted R² performance while maintaining interpretability

---

## Final Outcomes

- Built a statistically interpretable housing valuation model
- Achieved strong predictive performance on Kaggle-style evaluation data
- Ranked **2nd place** on the final leaderboard using RMSE evaluation
- Produced a complete end-to-end statistical modeling workflow in R

---

## Repository Structure

```text
statistical-housing-valuation/

├── data/
│   ├── HousePriceTrain.csv
│   └── DataDictionary.xlsx

├── analysis/
│   └── housing_price_mlr_analysis.Rmd

├── reports/
│   └── housing_price_mlr_report.pdf

├── visuals/
│   ├── saleprice_distribution.png
│   ├── predictor_correlation_matrix.png
│   ├── final_model_diagnostics.png
│   └── model_results_summary.png

└── README.md
```

---

## Tools & Methods

- R
- Multiple Linear Regression (MLR)
- Feature Engineering
- Regression Diagnostics
- VIF Analysis
- RMSE Evaluation
- Exploratory Data Analysis (EDA)
- Statistical Modeling
- Data Transformation

---

## Portfolio Positioning

This repository is intentionally positioned as:

- a statistical modeling case study
- an interpretable predictive analytics project
- a feature engineering and diagnostics workflow
- a classical statistics-focused machine learning project

The project emphasizes statistical reasoning, interpretability, and model reliability rather than black-box prediction alone.
