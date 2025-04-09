# Liocinema-Jotstar-Merger-Analysis-

This project is a Power BI Dashboard that analyzes subscriber behaviors including plan upgrades, downgrades, churn, and monthly revenue patterns. It provides a clear visualization of how users interact with different subscription plans over time.

## 🧩 Features

- **Plan Change Tracking:** 
  - Upgrade vs Downgrade trend analysis.
  - Filters by date and plan types.

- **Revenue Insights:**
  - Monthly recurring revenue (MRR) trends.
  - Impact of plan changes on total revenue.

- **Churn Analysis:**
  - Count of users who canceled their subscriptions.
  - Monthly churn breakdown and reasons.

- **Interactive Filters:**
  - Select by new plan, previous plan, and month/year.
  - Slicers to focus on specific time frames and behaviors.

## 📁 Data Sources

- **Table 1:** Subscriber data (`leocinema__db subscribers`)  
  Columns used: `subscription_plan`, `new_subscription_plan`, `plan_change_date`, `is_cancelled`

- **Table 2:** Pricing data  
  Columns used: `subscription_plan`, `monthly_price`

## 🛠️ Tools Used

- Power BI (Data Modeling, DAX, Visualization)
- DAX Measures (for plan change classification, churn calculation, and revenue calculation)

## 🧠 Key Insights

- Identified monthly spikes in upgrades/downgrades.
- Found correlation between downgrades and eventual churn.
- Revenue increased during promotional upgrades.
- Basic → Premium was the most common upgrade path.

## 📌 About

Created by **Saumya Jha**, aspiring data analyst with a passion for transforming raw data into compelling visual stories.  
This dashboard simulates a streaming platform's subscription data and was built for learning, portfolio, and presentation purposes.

---

## 📸 Dashboard Link:-
https://app.powerbi.com/view?r=eyJrIjoiNGM4YWY1YjItZjc4ZS00ODc4LWJlYTUtYWQ4MDdjMjgwYjU5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

