# Analyze A/B test results
This project has been completed as part of the [Udacity's Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) requirements.

## Overview
In this project, A/B tests have been conducted to test the user conversions of a new and an old webpage.
That is, I tested the rate of users who decided to pay for a company's product using the new webpage against those using the old webpage.
The goal is to understand whether the company should implement the new webpage or not.

The following steps have been performed:

- Handle mismatches between user groups and page assignment
- Clean the data
- Hypothesis testing:
	- Set up hypothesis testing (null and alternative hypothesis)
	- Sampling distribution for 10,000 simulations with bootstrapping, and p-value calculation
	- Statsmodels built-in operations (better computation performance than bootstraping with a large number of simulations), and p-value calculation
	- Logistic regression to predict if a user will convert or not
	- Multiple regression
- Discussion and conclusions

## Statistical Analysis

- Sampling distributions with bootstrapping (numpy.random.choice) and p-value calculations
- Statsmodels.api
	- Z-score test
	- P-value
	- Logit (logistic regression and multiple regression)

## Technologies used

- Python
- Libraries: NumPy, Pandas, Statsmodels, Random, MatPlotlib
- Jupyter Notebook

## Key Findings