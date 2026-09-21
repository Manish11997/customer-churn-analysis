# Customer Churn Analysis

**Business question:** Which customers are leaving, and why?

## Tools
Python (Pandas, NumPy, Matplotlib, Seaborn), SQLite, Jupyter Notebook

## What I did
- Extracted customer, subscription and support tables from a SQLite database
- Cleaned and standardized the data (data types, gender values, missing countries)
- Engineered features: churn flag, complaint count, tenure, churn-risk segments
- Calculated KPIs: churn rate, retention, ARPU, average tenure, escalation rate
- Visualized churn by month, plan, state, plus a correlation heatmap

## Key findings
- Overall churn: 27% (73% retention)
- Basic plan churn: 39% vs Premium: 14%
- Referral-acquired customers churn at 51% vs 12% for organic
- Escalated complaints show a strong correlation with churn (0.64)

## Recommendations
- Review the quality of the referral channel
- Prioritize fast resolution of escalated complaints
- Improve the value of the Basic plan or offer upgrade incentives

## Dataset
200 customers (sample dataset).

## Files
- `Churn_Analysis.ipynb`: full analysis
- `customer_churn.db`: SQLite database
- `images/`: chart previews
