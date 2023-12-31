# IDA-Project
Group G03 IDA Project

Topic 3 : Regression analysis for establishing a relation between response and regressor variables

Reference : [SF Salaries Dataset](https://www.kaggle.com/datasets/kaggle/sf-salaries)

# Employee Salary Analysis

## Overview
The database contains salary information of different employees in various organizations. The objective is to analyze whether Overtime Pay, Other Pay, and benefits collectively increase with Basic Pay for the year 2014.

## Regression Analysis
- **Simple Linear Regression Analysis:** We performed a simple linear regression analysis to investigate the relationship between Basic Pay and the combined effect of Overtime Pay, Other Pay, and benefits.
- **Simple Non-linear Regression Analysis with Degree 2:** We extended our analysis by applying a simple non-linear regression analysis with a polynomial equation of degree 2. This approach allows us to capture potential curvilinear relationships in the data.
- **Simple Non-linear Regression Analysis with Degree 3:** To explore further complexities, we conducted another non-linear regression analysis, this time with a polynomial equation of degree 3. This approach can better capture intricate relationships between variables.

## R^2 Values Calculation
- **Simple Linear Regression Analysis:** The R^2 value obtained from the simple linear regression model indicates the proportion of the variance in the dependent variable (combined effect of Overtime Pay, Other Pay, and benefits) that is predictable from the independent variable (Basic Pay) in a linear manner.
- **Simple Non-linear Regression Analysis with Degree 2:** The R^2 value for the non-linear regression analysis with a polynomial equation of degree 2 reflects how well the model fits the data while considering a quadratic relationship between Basic Pay and the combined effects.
- **Simple Non-linear Regression Analysis with Degree 3:** The R^2 value for the non-linear regression analysis with a polynomial equation of degree 3 measures the goodness of fit of the model when accounting for potential cubic relationships among the variables.

## Conclusion
Through our analysis using different regression techniques, we aimed to understand the relationship between Basic Pay and the cumulative impact of Overtime Pay, Other Pay, and benefits. The R^2 values obtained from each analysis provide insights into the explanatory power of the models. These results contribute to a comprehensive understanding of how these variables interact.

