# SaaS-Customer-Retention-Model

CLV, CAC, churn, and cohort insights to optimize SaaS growth and retention.

---

## Problem Statement

Businesses often prioritize customer acquisition volume over customer quality and retention. 

This project reframes the focus to examine **profitability per customer**, using strategic KPIs like **Customer Lifetime Value (CLV)** and **Customer Acquisition Cost (CAC)** — providing executives with a data-driven lens on where true growth lies.

---

## Dataset Overview

- **Type**: Simulated SaaS/subscription dataset  

- **Key Fields**:
  - `Customer ID`
  - `Subscription Type`
  - `Monthly Revenue`
  - `Months Retained`
  - `Signup Date`
  - `Customer Acquisition Cost (CAC)`

---
## Key Metrics Calculated

- **Customer Lifetime Value (CLV)** = Monthly Revenue × Months Retained  
- **CLV:CAC Ratio** = Profitability Efficiency Metric  
- **Churn Rate** = % of customers lost over time  
- **Retention by Cohort** = Retained revenue by signup group  
- **Tenure** = How long customers stay and how much they generate

---

## Visualizations

### 1. **Monthly Revenue vs. Churned (Lost) Revenue Over Time**

- This visualization helps identify the **net revenue impact** by showing how churned customers affect overall revenue growth.

### 2. **Revenue by Customer Acquisition Cost (CAC)**

- Displays which **acquisition channels** are providing the best value for the cost of acquiring customers.

### 3. **Revenue per Customer vs. Months Active**

- Illustrates how **customer longevity** impacts total revenue, highlighting long-term customer value.

### 4. **Churn Rate vs. CAC**

- Highlights the relationship between **churn** and **acquisition cost**, pointing out channels that may need improvement.

### 5. **Subscription Tenure: Where Loyalty Fuels Revenue**

- Breaks down revenue by **customer lifespan**, showing the **long-term value** of customer loyalty.

### 6. **Revenue Retention by Customer Cohort**

- Tracks **revenue retention** over time by customer cohort, showing how groups perform at different stages of their lifecycle.

### 7. **Revenue Trendline: Where We’ve Been, Where We’re Headed**

- Demonstrates the overall **revenue growth trend**, with clear **peaks and stable bases** that can help forecast future growth.

---

## General Trends/Insights

- **Premium customers** show the **highest CLV:CAC ratio (>3)**, reflecting a strong return on investment for customer acquisition.

- **Standard-tier customers** display **moderate retention** but have a **break-even CLV:CAC ratio (~1.6)**, indicating room for improvement.

- **Basic-tier customers** are **unprofitable**, with a **low CLV:CAC ratio (<1.5)** and high churn, suggesting potential for re-targeting or price adjustments.

- **Churn is highest in the early months** (Months 1–3), signaling the need for stronger **onboarding and early engagement strategies**.

- **Cohort analysis** reveals that **customers acquired during promotional periods** retain better and contribute more to revenue.

---

## Tools Used

- **Tableau** — Interactive dashboard and data visualizations  

- **Excel** — Data wrangling & calculated fields  

- **SQL** — Data extraction and preparation 

---

## Limitations

- **CAC values are estimated** due to the lack of marketing channel-specific data.

- **Simulated data** does not capture real-world external factors like pricing changes, customer support interactions, or seasonal variations.

- **CLV assumes a linear revenue model**, which may not reflect actual user behavior in dynamic subscription models with upgrades or fluctuating usage.

---

## Acknowledgements

- This analysis was inspired by industry-standard **SaaS KPIs** and executive dashboard best practices.

- Thank you to **OpenAI** for assistance with Tableau logic and modeling techniques.

- Dataset structure and visualization style modeled after widely-used **churn analysis** and **CLV reporting** templates.

---

## Next Steps (Optional for Future Work)

- Incorporate **marketing attribution data** for a more granular analysis of CAC by source.

- **Machine learning-based churn prediction** using behavioral data.

- Add segmentation by **geography, device**, or **usage** to improve targeting and revenue forecasting.


