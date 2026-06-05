# 🎯 Ensuring KPI Reliability

## Handling Data Grain Mismatch in Business Dashboards

---

## 📌 Project Overview

This case study originated during the development of an **E-Commerce Sales & Profitability Dashboard**, where an investigation into sales targets uncovered a **critical data-grain mismatch** that produced misleading KPI comparisons.

The original objective was to compare **actual sales performance against sales targets** using KPIs and Power BI visuals. However, during dashboard development, I identified a **data reliability issue** that made target-based comparisons analytically unreliable.

Rather than forcing technically correct but misleading metrics, I reframed the work into a focused case study on **KPI reliability, data-grain mismatch, and analyst decision-making**.

The project demonstrates how validating data structure and reporting logic is often as important as building dashboards, ensuring that business decisions are based on trustworthy and decision-ready analytics.

---

## ❗ Problem Identified

While working with the data, I observed a fundamental mismatch in data grain:

### Sales Data

* Transaction-level data with a clear **time dimension (month-wise)**
* Suitable for trend analysis and time-based KPIs

### Sales Target Data

* Available only at the **category level**
* No month or date information provided

When the target table was joined with sales data and visualized over time:

* Category-level targets repeated across multiple months
* KPIs appeared technically correct but became analytically misleading
* Dashboards falsely suggested target achievement despite unsupported business reality

As a result, the analysis risked producing **incorrect business conclusions**.

---

## ⚠️ Why This Was a Serious Business Risk

I recognized that unreliable KPIs could create meaningful decision risk:

* Leadership may believe performance is stronger than reality
* Business decisions could be based on misleading KPIs
* Teams may be rewarded or evaluated unfairly
* Trust in dashboards and analytics could be weakened

In business analytics, technically correct calculations are not always analytically correct.

---

## ✅ Analyst Decision

Instead of forcing target-based KPIs or artificially adjusting visuals, I made a conscious decision to **remove or de-emphasize unreliable target metrics** where the data grain did not support fair comparison.

I prioritized:

* Honest analysis over visually impressive dashboards
* Decision quality over misleading KPIs
* Reliable business interpretation over forced reporting

---

## 🔁 What I Did Instead

I shifted the analysis toward **reliable, actual-based metrics**, including:

* Total Sales
* Total Profit
* Profit Margin
* Orders
* Average Order Value (AOV)

Using these metrics, I focused on:

* Margin pressure analysis
* Loss-making regions
* Customer-level profitability
* Reliable operational performance insights

This ensured the dashboard remained **accurate, interpretable, and decision-ready**.

---

## 🧠 Key Learnings

This project reinforced an important analyst mindset:

Before creating KPIs or visuals, I now ask:

* Does the data grain align across tables?
* Will joins duplicate or inflate values?
* Can this metric support time-based analysis fairly?
* Is the insight technically correct **and** analytically reliable?

---

## 🎯 Final Takeaway

A strong data analyst protects **decision quality and trust in analytics** — even when that means removing popular KPIs instead of forcing attractive but unreliable visuals.

---

## 🔗 Relationship to Other Projects

* **Project 1 – SQL Case Study** → Answering business questions through analysis
* **Project 2 – Power BI Dashboard** → Communicating business insights
* **Project 3 – KPI Reliability & Judgment** → Ensuring trustworthy and decision-ready analytics
