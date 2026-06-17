# Credit Behaviour Analysis & Risk Assessment

## Overview
This project performs a structured, end-to-end analysis of credit behaviour data from a financial institution. Using three raw datasets covering loan applications, credit enquiries, and tradeline activity across 74,300 client records, the analysis uncovers patterns in credit usage, loan approval rates, and risk profiles to support data-driven lending decisions.

## Dataset
- **base_file** — 24,800 clients: loan application and approval data
- **enquiry_data** — 24,500 clients: credit enquiry counts (6m / 1y / 2y)
- **tradeline_data** — 25,000 clients: tradeline counts and max spending (6m / 1y / 2y)

## Project Stages
| Stage | Focus |
|---|---|
| 1. Understanding the Data | Client coverage, duplicate checks, missing value detection, logical consistency |
| 2. Data Cleaning | Imputation, negative value correction, consistency fixes, winsorisation |
| 3. Univariate Analysis | Distribution of tradelines, enquiries, spending, approval rates |
| 4. Bivariate Analysis | Correlations between credit activity, spending, and loan approvals |
| 5. Feature Engineering | Loan approval rate, credit utilisation rate, time-weighted enquiry score |
| 6. Advanced Analysis | Risk profiling, client segmentation, engagement vs approval analysis |

## Key Findings
- **79.7%** of clients applied for at least one loan; overall approval rate is **0.60**
- Clients applying 4 times receive ~2 approvals on average vs ~0.80 for one-time applicants
- Credit activity (tradelines) and enquiry frequency are statistically independent (correlation = 0.01)
- Average credit utilisation rate ≈ **1.00** — a significant financial stress indicator
- Spending level and client engagement do not meaningfully influence loan approval outcomes

## Tools
Microsoft Excel — formulas, VLOOKUP joins, IQR outlier detection, summary statistics, histogram charts
