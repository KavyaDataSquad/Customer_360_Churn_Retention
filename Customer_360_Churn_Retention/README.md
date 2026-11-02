# Customer 360 | Churn & Retention

A customer analytics project using the Telco Customer Churn dataset. It combines SQL, Python EDA, and a Power BI dashboard to explore churn patterns and retention opportunities.

## Business questions
- What is the overall customer churn rate?
- Which contract and tenure segments show higher churn?
- How do service adoption and payment methods relate to churn?
- What monthly recurring charges are associated with churned customers?

## Dataset snapshot
- Customers: **7,043**
- Churned customers: **0**
- Overall churn rate: **nan%**
- Monthly charges associated with churned customers: **$0.00** (exposure indicator, not forecast revenue loss)

## Included assets
- `Telecom_Customer_Churn.pbix`: Power BI report.
- `Customer_Churn_Analysis.sql`: SQL setup and analysis queries, including added contract/tenure segmentation.
- `Customer_churn.ipynb`: Python cleaning and exploratory analysis.
- CSV dataset(s) and dashboard preview images.
- `Reports/Customer_Retention_Analysis.md`: recalculated KPI summary.

## How to explore
1. Import the source CSV into MySQL and align the table/column names with the SQL script.
2. Run the notebook from top to bottom.
3. Open the PBIX in Power BI Desktop; update source paths and refresh if required.
4. Review the analysis notes and dashboard pages.

## Skills demonstrated
SQL, Python/Pandas, data cleaning, customer segmentation, churn KPIs, Power BI, DAX, data visualization, business recommendations.

## Source note
Adapted portfolio version of the supplied Telecom Customer Churn & Retention Analysis project. Existing data, notebook, and report assets are retained; additional analysis and documentation are added. Review upstream source attribution before redistribution.
