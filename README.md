# Exploratory Data Analysis of Credit Card Default Risk
## Introduction
This project analyzes the Default of Credit Card Clients dataset obtained from the UCI Machine Learning Repository. The dataset contains information on 30,000 credit card holders in Taiwan, including demographic information, credit limits, bill statements, previous payments, and whether the client defaulted on their payment in the following month.

Credit card default is a major concern for financial institutions because it can lead to significant financial losses. By analyzing customer characteristics and payment behaviour, financial institutions can better understand factors associated with default risk and improve credit risk management.

Dataset:
https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

## Problem Statement
Financial institutions must identify customers who are more likely to default on their credit card payments. Understanding the relationship between customer demographics, credit limits, payment history, and default behaviour can help banks make better lending decisions and reduce financial risk.

This study aims to answer the following questions:
1. What proportion of customers default on their credit card payment?
2. Does gender influence default behaviour?
3. Does education level affect default rates?
4. How does credit limit relate to default?
5. Which variables have the strongest relationship with default?

## Hypothesis 
Null Hypothesis (H₀):
There is no statistically significant linear relationship between the selected independent variables (e.g., credit limit, repayment status, bill amounts, payment amounts, and age) and credit card default.

Alternative Hypothesis (H₁):
There is a statistically significant linear relationship between one or more of the selected independent variables and credit card default.

### Statistical Significance Analysis
The following hypotheses were formulated to determine whether selected customer characteristics are significantly associated with credit card default.

#### Hypothesis 1: Gender

H₀: There is no significant association between gender and credit card default.

H₁: There is a significant association between gender and credit card default.

#### Hypothesis 2: Education Level

H₀: There is no significant association between education level and credit card default.

H₁: There is a significant association between education level and credit card default.

#### Hypothesis 3: Marital Status

H₀: There is no significant association between marital status and credit card default.

H₁: There is a significant association between marital status and credit card default.

#### Hypothesis 4: Credit Limit

H₀: There is no significant difference in the mean credit limit between customers who defaulted and customers who did not default.

H₁: There is a significant difference in the mean credit limit between customers who defaulted and customers who did not default.
