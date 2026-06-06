# Simple Linear Regression – Marketing ROI Analysis

## Author
**Palmer Ogiriki**

---

## Project Overview
This project applies Simple Linear Regression to a marketing dataset to analyze the impact of advertising channels (TV, Radio, and Social Media) on Sales. The objective is to identify the most effective marketing channel for improving Return on Investment (ROI).

The project covers the full data science workflow:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Model building using Ordinary Least Squares (OLS)
- Assumption testing and diagnostics
- Interpretation of results for business decisions

---

## Dataset
The dataset contains marketing expenditure and sales data, including:

- TV advertising budget  
- Radio advertising budget  
- Social Media advertising budget  
- Sales (target variable)

---

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels

---

## Project Workflow

### 1. Data Cleaning
- Removed missing values
- Checked data types and structure
- Ensured dataset consistency

### 2. Exploratory Data Analysis (EDA)
- Correlation matrix analysis
- Scatter plots for feature relationships
- Identified the strongest predictor of Sales

### 3. Model Building
- Selected TV advertising as the independent variable
- Built a Simple Linear Regression model using OLS (statsmodels)
- Evaluated coefficients, p-values, and R-squared

### 4. Model Diagnostics
- Linearity check
- Normality of residuals (Histogram & Q-Q Plot)
- Homoscedasticity check (Residual plot)

---

## Key Findings
- TV advertising has the strongest positive correlation with Sales
- The regression model is statistically significant
- A large proportion of Sales variation is explained by TV spending
- Model assumptions are reasonably satisfied

---

## Business Insight
Increasing investment in TV advertising is expected to generate the highest ROI compared to Radio and Social Media advertising channels.

---

