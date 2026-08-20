# Exploratory Data Analysis Summary

## Dataset Overview

The dataset contained 500 customer records used to analyze factors associated with account delinquency.

## Data Quality Assessment

The analysis identified:

- 39 missing Income values
- 2 missing Credit Score values
- 29 missing Loan Balance values
- Employment Status inconsistencies
- Credit Utilization values above 100% requiring investigation

Median imputation was used for applicable missing numeric values, while inconsistent employment-status labels were standardized.

## Delinquency Overview

- Total Customers: 500
- Non-Delinquent Customers: 420
- Delinquent Customers: 80
- Overall Delinquency Rate: 16.0%

## Risk-Factor Analysis

### Missed Payments

Customers with 5 missed payments had the highest observed delinquency rate of 22.1%.

The relationship was not consistently linear across all missed-payment levels.

### Credit Utilization

High-utilization customers had an observed delinquency rate of 17.4%, compared with 12.0% for low-utilization customers.

### Debt-to-Income Ratio

Average DTI was slightly higher among delinquent customers than non-delinquent customers.

## Key Insight

Missed payments, credit utilization, and debt-to-income ratio were identified as useful risk indicators.

However, the analysis does not establish causation, and multiple variables should be considered together.
