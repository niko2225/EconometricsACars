# Econometric Analysis of the U.S. Automobile Market

**Final project – Econometrics A, University of Copenhagen (2026)**

## Overview

This project examines demand in the U.S. automobile market using product-level data on vehicle sales, prices, and characteristics.

The main objective is to estimate demand relationships and investigate the economic implications of price endogeneity. The analysis applies econometric methods to estimate price sensitivity and derive measures of marginal costs and markups.

## Methods

The project applies several econometric techniques:

- **Ordinary Least Squares (OLS):** Estimation of baseline demand models.
- **Instrumental Variables (2SLS):** Addressing potential price endogeneity using instrumental variables.
- **Fixed Effects:** Accounting for unobserved heterogeneity.
- **Instrument diagnostics:** Evaluating instrument relevance and validity.
- **Monte Carlo simulation:** Investigating the statistical properties of estimators.

The estimated models are further used to calculate price elasticities, marginal costs, and markups.

## Data

The analysis uses product-level data from the U.S. automobile market, covering vehicle sales, prices, and product characteristics.

Variables include:

- Sales and market shares
- Prices
- Horsepower and fuel efficiency (MPG)
- Vehicle dimensions and weight
- Vehicle type

**Note:** The original course dataset is not included in this repository. The notebook therefore requires access to the dataset locally to reproduce the full analysis.

## Technologies

- Python
- pandas
- NumPy
- statsmodels
- linearmodels
- Matplotlib
- Jupyter Notebook


## Academic Context

Completed as the final project in **Econometrics A** at the University of Copenhagen, 2026. The project was also presented at an oral examination.
