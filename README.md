# 📊 Dollar Bank: End-to-End Customer Churn Analytics
![SQL](https://img.shields.io/badge/Exploratory_Analysis-SQL-blue?style=flat-square&logo=microsoft-sql-server)
![Python](https://img.shields.io/badge/Deep_Dive_EDA-Python-darkgreen?style=flat-square&logo=python)
![Tableau](https://img.shields.io/badge/Business_Intelligence-Tableau-orange?style=flat-square&logo=tableau)

An end-to-end data analytics and strategic business intelligence solution investigating customer attrition patterns within the credit card division of **Dollar Bank**. This repository details a comprehensive analysis pipeline—spanning relational data exploration using **SQL**, rigorous programmatic diagnostics via a **Python Jupyter Notebook**, and interactive executive monitoring built in **Tableau**.

---

## 📈 Executive Performance Baseline (KPIs)

| 16.0% | $4,404 | $3,095 | 20% ➔ 80% |
| :---: | :---: | :---: | :---: |
| **Current Churn Rate** <br>*(Industry Target: < 7%)* | **Average Client Spend** <br>*(All Accounts)* | **Average Churn Spend** <br>*(Lost Accounts)* | **Pareto "Vital Few"** <br>*(Strategic Target Segment)* |

---

## 🏢 Business Case & Project Objective
Dollar Bank noticed a steady increase in customer attrition within its credit card services. As a Senior Data Analyst, I was brought in to analyze customer data, find the main reasons behind this churn, and deliver actionable, data-backed recommendations to improve retention and protect business revenue.

---

## 🛠️ Data Architecture & Methodology

```mermaid
graph TD
    A[Raw Bank Datasets] --> B[SQL: Multi-Table Joins & Validation]
    B --> C[Python: Outlier Checking, Quality Verification & EDA]
    C --> D[Tableau: Interactive Dashboard Optimization]
    D --> E[Business Strategy & Retention Interventions]
1. Relational Engineering (SQL)
Leveraged complex multi-table joins to unify three disparate internal banking tables.

Established a clean master dataset to query baseline attrition metrics and track demographic behavior.

2. Deep-Dive Diagnostics (Python)
Performed feature variable typing, verified missing records, and isolated behavioral outliers.

Conducted multi-variable distribution evaluations and built a cross-correlation matrix to uncover the early signals of customer detachment.

View Python Notebook (Update with actual link)

3. Interactive Visualization (Tableau)
Developed an executive-facing business intelligence interface mapping demographic shifts and spending anomalies.

Implemented interactive filtering loops to let stakeholders drill down into account age groups and income brackets on the fly.

Access Live Tableau Dashboard (Update with actual link)

🔍 Core Analytical Insights
💳 Transactional Indicators & Behavioral Thresholds
Activity Drops: Customers who completed fewer than 100 total transactions and spent less than $5,000 over their lifetime showed the highest risk of churn, regardless of income bracket.

Spend Disparity: Churned accounts held an average spending floor of $3,095, which is roughly 30% lower than the active customer average of $4,404. This drop-off serves as a reliable early warning indicator for customer success teams.

👥 High-Risk Demographic Clusters
Gender & Age Profile: Female clients aged 41–50 represented the largest single attrition spike, accounting for 4.4% of the total customer loss within that segment.

Account Tenure Vulnerability: Customer attrition peaks among established accounts (25–36 months of tenure) at 5.0% for women and 3.6% for men. This indicates a clear gap in onboarding engagement once an account moves past its second year.

Card Tier Concentration: The largest single group of churned accounts (559 customers) consisted of female Blue Card holders earning less than $40k, followed closely by male Blue Card holders earning $80k–$120k (215 customers).

   Attrition Matrix by Product / Income Group:
   [Blue Card Tier] ───► Low Income (<$40k) Female Accounts  ───► 559 Churned
                    ───► Mid-High ($80k-$120k) Male Accounts ───► 215 Churned
🎯 Pareto Analysis ("The Vital Few")
The analysis verified that 20% of churned customer segments are driving roughly 80% of total customer attrition.

The dashboard isolates two primary high-impact clusters within this group: Female graduates (married or single) and Male graduates (single).

🚀 Strategic Recommendations & Action Plan
By deploying highly targeted marketing campaigns and product improvements focused on these specific "Vital Few" segments, Dollar Bank can reduce its overall churn rate from 16% down to an industry-standard 7%.

1. Tailored Life-Stage Resource Hubs
Action: Provide tailored financial literacy tracks, webinars, and loan repayment toolkits to young single and married graduates.

Goal: Increase brand affinity by helping younger customers manage debt and build credit responsibly.

2. Micro-Targeted Strategic Partnerships
Action: Launch co-branded partnership perks (e.g., fitness network credits, active lifestyle discounts) tailored specifically to younger graduate segments.

Goal: Embed the bank's credit cards directly into the daily spending habits of these high-velocity consumers.

3. Dedicated Customer Anniversary Loyalty Programs
Action: Create an automated milestone reward system specifically targeting accounts approaching the critical 25-to-36 month tenure window.

Goal: Counteract mid-tenure churn by offering annual fee waivers, free investment planning sessions, or points multipliers.

4. Specialized Financial Inclusion & Counseling Services
Action: Introduce proactive credit monitoring and financial wellness counseling tools for Blue Card holders earning under $40k.

Goal: Reduce financial anxiety, lower default risks, and build long-term account loyalty.


---
*Developed as part of a portfolio project investigating financial service customer retention models.*
