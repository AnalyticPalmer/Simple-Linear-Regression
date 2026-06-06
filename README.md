# Simple Linear Regression – Marketing ROI Analysis

## Author

**Palmer Ogiriki**

---

## Project Overview

This project applies Simple Linear Regression to a marketing dataset to evaluate the relationship between advertising expenditure and sales performance. The primary objective is to determine which advertising channel has the strongest impact on Sales and provide data-driven recommendations for optimizing marketing budget allocation.

The analysis follows a complete data science workflow, including:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Correlation analysis
* Model development using Ordinary Least Squares (OLS)
* Assumption testing and diagnostics
* Interpretation of results and business recommendations

---

## Dataset

The dataset contains information on marketing expenditures across different advertising channels and the corresponding sales generated.

### Features

* **TV** – TV advertising budget
* **Radio** – Radio advertising budget
* **Social Media** – Social media advertising budget
* **Sales** – Product sales (target variable)

---

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Cleaning and Preparation

* Loaded the dataset into Python.
* Checked for missing values and inconsistencies.
* Removed or handled missing records where necessary.
* Verified data types and overall data quality.

### 2. Exploratory Data Analysis (EDA)

* Examined summary statistics.
* Generated scatter plots to visualize relationships between advertising channels and Sales.
* Created a correlation matrix to identify the strongest predictor of Sales.

### 3. Variable Selection

Based on the correlation analysis, **TV advertising** showed the strongest positive relationship with Sales and was selected as the independent variable for the Simple Linear Regression model.

### 4. Model Building

* Built a Simple Linear Regression model using Ordinary Least Squares (OLS).
* Used TV advertising expenditure as the predictor variable.
* Evaluated model performance using regression coefficients, p-values, and R-squared.

### 5. Assumption Testing

The following regression assumptions were assessed:

#### Linearity

* Verified using a scatter plot with a regression line.

#### Normality of Residuals

* Evaluated using a histogram and Q-Q plot.

#### Homoscedasticity

* Assessed using a residuals versus fitted values plot.

---

## Model Results

### Regression Equation

```text
Sales = 7.03 + 0.0475(TV)
```

### R-Squared Value

```text
R² = 0.61
```

This indicates that approximately **61% of the variation in Sales** can be explained by TV advertising expenditure.

### Statistical Significance

```text
TV p-value < 0.05
```

The p-value is below the 0.05 significance level, indicating that TV advertising is a statistically significant predictor of Sales.

---

## Key Findings

* TV advertising has the strongest positive correlation with Sales.
* The regression model is statistically significant.
* TV advertising explains a substantial proportion of the variation in Sales.
* Diagnostic plots indicate that the key assumptions of Simple Linear Regression are reasonably satisfied.
* Increased TV advertising expenditure is associated with increased Sales performance.

---

## Business Insight

The analysis suggests that TV advertising delivers the strongest impact on Sales among the available marketing channels. Organizations seeking to maximize marketing return on investment (ROI) should consider allocating a larger share of their advertising budget to TV campaigns while continuing to monitor the effectiveness of other channels.

---

## Conclusion

This project successfully applied Simple Linear Regression to analyze the relationship between advertising expenditure and Sales performance. Through data cleaning, exploratory data analysis, model development, and assumption testing, TV advertising was identified as the most influential predictor of Sales.

The model demonstrated a statistically significant relationship between TV advertising and Sales, with an R-squared value of 0.61, indicating that TV advertising explains a meaningful portion of Sales variability. Based on these findings, increasing investment in TV advertising is expected to produce the highest return on marketing spend and support improved business performance.

---

## Repository Structure

```text
marketing-regression-project/
│
├── Simple Linear Regression.ipynb
├── marketing_and_sales_data_evaluate_lr.csv
├── requirements.txt
└── README.md
```

---

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook and open the project notebook:

```bash
jupyter notebook regression_analysis.ipynb
```
