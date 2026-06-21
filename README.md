# Amex Customer Portfolio Segmentation

## Business Problem
Credit card issuers need to understand the composition of their customer portfolio to design targeted marketing strategies, identify high-value segments, and flag early signs of customer disengagement. This project segments credit card customers based on spending behavior, payment patterns, and credit utilization to surface actionable customer groups.

## Dataset
**Source:** [Credit Card Customer Data](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata) (Kaggle, by arjunbhasin2013)
~9,000 active credit card holders, 18 behavioral variables including balance, purchase frequency, cash advance frequency, credit limit, and payments. See `data/README.md` for download instructions.

## Objective
Segment customers into meaningful groups (e.g., high-value revolvers, transactors, dormant accounts, cash-advance-heavy users) using SQL-based RFM-style analysis, and translate these segments into marketing recommendations.

## Tools Used
- SQL (window functions, CTEs, aggregate scoring)
- [Add: SQLite / PostgreSQL / MySQL — whichever you use]

## Approach
1. Data cleaning and exploration
2. Calculated Recency, Frequency, and Monetary-equivalent metrics from purchase and payment behavior
3. Scored and bucketed customers into segments using SQL CASE logic and window functions
4. Profiled each segment by average balance, credit limit utilization, and payment behavior

## Key Insight
> *[Fill in once analysis is done — e.g., "Segment C (18% of customers) carries 40% of total revolving balance but has the lowest full-payment rate, indicating concentrated credit risk worth monitoring."]*

## Recommendation to Stakeholders
> *[Fill in — e.g., "Target Segment A (high frequency, low balance) with loyalty/rewards campaigns; flag Segment C for proactive risk-based outreach before delinquency risk increases."]*

## Repo Structure
```
├── data/           → dataset source info
├── queries/        → SQL scripts
├── images/         → output screenshots/charts
└── README.md
```
