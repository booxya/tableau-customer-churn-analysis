# Customer Churn Analysis (Tableau)

Interactive Tableau dashboard analysing the Telco Customer Churn dataset (Kaggle).
It highlights overall churn rate, key drivers (contract, internet service, payment method),
and demographic segments (gender, senior citizen, partner, dependents).

## Dataset
- Source: Telco Customer Churn (Kaggle)
- Size: 7,043 customers, 21 fields

## Business Questions
1) What is the overall churn rate?
2) Which factors drive churn the most (contract type, internet service, payment method)?
3) Are there demographic patterns (senior citizens, partner, dependents, gender)?
4) What actions can reduce churn?

## Key Metrics (KPI)
- Churn Rate: ~26.5%
- Customers: 7,043
- Avg Monthly Charges: $61.27 (active) vs $74.44 (churned)

## Insights
- Highest risk segments:
  - Month-to-month contract (≈42.7%)
  - Fiber optic internet (≈41.9%)
  - Electronic check payments (≈45.3%)
- Lower risk:
  - 2-year contract (≈2.8%), DSL (≈19%)
- Demographics:
  - Senior citizens churn more (~41.7% vs ~23.6%)
  - Customers with dependents/partner churn less

## Recommendations
- Incentivize longer contracts (upgrade offers/discounts).
- Migrate at-risk customers away from electronic check to auto-pay.
- Targeted retention program for fiber-optic users and senior citizens
  (enhanced support, plan reviews, loyalty perks).


## How to view
- Tableau Public link: <https://public.tableau.com/app/profile/joanna.wasilenko/viz/tableau-customer-churn-analysis/Dashboard1>
- or open the `.twbx` in Tableau Desktop.

## Next Steps (roadmap)
- Add scatterplot: MonthlyCharges vs Tenure (colored by churn)
- Cohort (tenure) analysis and retention curve
- Actions/filters to drill from segment → customer list
- Optional SQL/Python data prep notebook

---

**Author**: Joanna Wasilenko 
Part of my **Data Analyst Portfolio**
