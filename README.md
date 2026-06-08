Multiple Linear Regression Evaluation

Project Overview

This project applies Multiple Linear Regression to analyze the impact of different marketing channels on Sales. The objective is to determine how TV, Radio, and Social Media advertising expenditures influence Sales and to provide data-driven recommendations for marketing budget allocation.

Dataset Description

The dataset contains the following variables:

- TV – Advertising expenditure on TV campaigns.
- Radio – Advertising expenditure on Radio campaigns.
- Social_Media – Advertising expenditure on Social Media campaigns.
- Sales – Sales generated from marketing activities.

Analysis Objectives

The project aims to:

1. Perform Exploratory Data Analysis (EDA).
2. Handle missing values and prepare the dataset.
3. Examine relationships among variables using correlation analysis.
4. Detect multicollinearity using Variance Inflation Factor (VIF).
5. Build a Multiple Linear Regression model using Statsmodels.
6. Evaluate model performance using Adjusted R-squared and p-values.
7. Validate regression assumptions using diagnostic plots.
8. Interpret regression coefficients in a business context.
9. Provide actionable marketing recommendations.

Tools and Libraries

The following Python libraries were used:

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scipy

Environment Setup

Install the required packages using:

pip install pandas numpy matplotlib seaborn statsmodels scipy

Methodology

Data Cleaning

- Checked for missing values.
- Removed incomplete records using "dropna()".

Exploratory Data Analysis

- Generated descriptive statistics.
- Created correlation matrices and visualizations.
- Examined relationships between predictors and Sales.

Multicollinearity Assessment

- Computed Variance Inflation Factor (VIF) values.
- Evaluated potential collinearity among predictors.

Multiple Linear Regression

- Used TV, Radio, and Social_Media as independent variables.
- Used Sales as the dependent variable.
- Built an Ordinary Least Squares (OLS) regression model.

Assumption Checking

The following diagnostic checks were performed:

- Residuals vs Fitted Plot (Linearity)
- Histogram of Residuals (Normality)
- Q-Q Plot (Normality)
- Residual Distribution Analysis

Key Findings

- TV, Radio, and Social Media advertising contribute to Sales performance.
- Multicollinearity was assessed using VIF statistics.
- Model performance was evaluated using Adjusted R-squared.
- Statistical significance was assessed using predictor p-values.
- Diagnostic plots were used to validate model assumptions.

Business Recommendation

Marketing investment should be prioritized toward channels that demonstrate statistically significant coefficients and the strongest positive impact on Sales. Decision-makers should use the regression results to allocate budgets more effectively and maximize return on marketing investment.

Repository Contents

- "multiple_regression_analysis.ipynb"
- "README.md"

Author

Ahmed Kolo
