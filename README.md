# Project 3: Ensuring KPI Reliability
## Handling Data Grain Mismatch in Business Dashboards
### 📌 Project Context
This project builds on Project 2 (Indian E-commerce Sales Analysis) and uses the same dataset.
My original goal was to analyze sales performance using actual metrics and compare them against sales targets through KPIs and Power BI visuals.
While building the dashboard, I identified a critical data reliability issue, which led me to treat this as a separate project focused on KPI accuracy.
________________________________________
### ❗ Problem I Identified
#### While working with the data, I noticed that:
•	Sales data had a clear time dimension (transaction-level, month-wise)
•	Sales targets were defined only at the category level, with no date or month information
#### When I joined the target table with sales data and visualized it month-wise:
•	The same category-level target repeated across multiple months
•	Visuals and KPIs showed targets being met
•	The calculations were technically correct, but the insight was misleading
As a result, the dashboard incorrectly suggested that targets were achieved, even though actual performance did not support that conclusion.
________________________________________
### ⚠️ Why I Considered This a Serious Business Risk
#### I realized this could have real consequences:
•	Leadership might believe performance was better than it actually was
•	Decisions could be made using incorrect KPIs
•	Teams could be rewarded or penalized unfairly
•	Most importantly, trust in the dashboard and analytics could be damaged
________________________________________
### ✅ My Analyst Decision
Instead of forcing target-based KPIs or trying to “fix” the visuals artificially, I made a conscious decision to remove or de-emphasize target-based KPIs where the data grain didn’t support fair time-based comparison.
I prioritized honest analysis over attractive but unreliable visuals.
________________________________________
### 🔁 What I Did Instead
I refocused the dashboard on reliable, actual-based metrics, including:
•	Total Sales
•	Total Profit
•	Profit Margin
•	Orders
•	Average Order Value (AOV)
Using these, I highlighted:
•	Margin pressure
•	Loss-making regions
•	Customer-level profitability
This ensured that the insights were accurate, interpretable, and trustworthy.
________________________________________
### 🧠 My Key Learnings
Before adding any KPI or visual, I now ask myself:
•	Does the data grain match across tables?
•	Will this join duplicate or inflate values?
•	Can this metric support time-based trends fairly?
________________________________________
### 🎯 Final Takeaway
A good data analyst protects decision quality — even if that means removing popular KPIs instead of forcing them.
________________________________________
## 📂 How This Fits With My Other Projects
•	Project 1: SQL Case Study — answering business questions
•	Project 2: Power BI Dashboard — communicating insights
•	Project 3: KPI Governance & Judgment — ensuring insight reliability

