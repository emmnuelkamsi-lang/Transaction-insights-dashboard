# Transaction-insights-dashboard
Power BI analysis of 50K e-commerce transactions — revenue drivers, customer segmentation, and a caught data-quality bug.

# Customer Transaction Insights

Power BI analysis of a 50,000-row e-commerce transactions dataset ([source](https://www.kaggle.com/datasets/smayanj/e-commerce-transactions)), built to identify where revenue actually comes from and turn that into marketing recommendations.

## Key findings
- $25.16M total revenue across 10 countries, 50K customers
- Senior customers generate the highest revenue ($12.3M), followed by Adults ($9.6M) — Youth trails well behind ($3.3M)
- Revenue is concentrated: the top 10 customers account for a disproportionate share of transactions

## Recommendations
- Strengthen engagement in top-revenue countries (France, Germany) with localized campaigns
- Focus marketing on Senior/Adult segments with loyalty programs and simplified purchase flows
- Grow Youth revenue with starter-tier products and social-first campaigns

## Data quality note
The "Total spending by purchase band" visual classified 100% of transactions as "High," with Medium and Low both at zero — a sign the segmentation thresholds were misconfigured rather than a real finding. Documented here since only the exported report is available; would rebuild with the live file.

## Tools
Power BI

## Files
- `transaction_insights.pdf` — exported report
