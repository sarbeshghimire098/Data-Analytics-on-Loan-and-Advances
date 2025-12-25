# Data Analytics on Loan and Advances

## Project Overview

This Jupyter Notebook (`Data Analytics on Loan and Advances.ipynb`) performs exploratory data analysis (EDA) and preparation on a loan dataset (`loan_data.csv`) containing customer and loan application information. The goal is to understand the characteristics of the data, identify patterns, and prepare it for potential predictive modeling (e.g., loan default prediction).

The dataset contains **50,000 rows** and includes a mix of numerical and categorical features related to borrowers and their loan applications.

## Dataset Description

The dataset (`loan_data.csv`) has the following columns:

| Column                      | Description                                      | Type       |
|-----------------------------|--------------------------------------------------|------------|
| `customer_id`               | Unique customer identifier                       | Categorical|
| `age`                       | Age of the applicant                             | Numerical  |
| `occupation_status`          | Employment status (Employed, Self-Employed, Student) | Categorical|
| `years_employed`            | Years of employment                              | Numerical  |
| `annual_income`             | Annual income of the applicant                   | Numerical  |
| `credit_score`              | Credit score                                     | Numerical  |
| `credit_history_years`      | Length of credit history in years                | Numerical  |
| `savings_assets`            | Value of savings/assets                          | Numerical  |
| `current_debt`              | Current outstanding debt                         | Numerical  |
| `defaults_on_file`          | Number of defaults on file (0/1)                  | Binary     |
| `delinquencies_last_2yrs`   | Number of delinquencies in last 2 years           | Numerical  |
| `derogatory_marks`          | Number of derogatory marks                       | Numerical  |
| `product_type`              | Type of product (Credit Card, Personal Loan, Line of Credit) | Categorical|
| `loan_intent`               | Purpose of the loan (Personal, Education, Medical, etc.) | Categorical|
| `loan_amount`               | Requested loan amount                            | Numerical  |
| `interest_rate`             | Interest rate offered                            | Numerical  |
| `debt_to_income_ratio`      | Debt-to-income ratio                             | Numerical  |
| `loan_to_income_ratio`      | Loan amount to income ratio                      | Numerical  |
| `payment_to_income_ratio`   | Estimated monthly payment to income ratio        | Numerical  |
| **Target**                  |                                                  |            |
| `loan_status`               | Loan outcome (1 = Default, 0 = Fully Paid)       | Binary     |

## Key Insights from Categorical Analysis

### Occupation Status
- **3 unique values**
- **Most common**: Employed (69.94%)
- Distribution:
  - Employed: 34,971 (69.94%)
  - Self-Employed: 10,179 (20.36%)
  - Student: 4,850 (9.70%)

### Product Type
- **3 unique values**
- **Most common**: Credit Card (44.91%)
- Distribution:
  - Credit Card: 22,455 (44.91%)
  - Personal Loan: 17,523 (35.05%)
  - Line of Credit: 10,022 (20.04%)

### Loan Intent
- **6 unique values**
- **Most common**: Personal (24.86%)
- Top intents:
  - Personal: 12,429 (24.86%)
  - Education: 10,134 (20.27%)
  - Medical: 7,598 (15.20%)
  - Business: 7,469 (14.94%)
  - Home Improvement: 7,453 (14.91%)
  - Debt Consolidation: 4,917 (9.83%)

## Notebook Structure

1. **Import Libraries**
   - `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`

2. **Load Data**
   - Reads `loan_data.csv`
   - Displays first few rows

3. **Categorical Features Analysis**
   - Detailed summary of categorical columns:
     - Unique value counts
     - Most frequent value
     - Top 10 value counts with percentages (styled table)

4. **(Planned/Upcoming Sections)**
   - Numerical feature analysis
   - Correlation analysis
   - Visualization (distributions, loan status breakdowns)
   - Feature engineering
   - Modeling (if extended)

## Requirements

To run this notebook locally:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
