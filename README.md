# Player-Funnel-and-Retention-Analysis
Project Overview

# This project analyzes player behavior in an online gaming/betting dataset to identify:

- Conversion funnel drop-offs from registration to first activity

- Retention & engagement patterns in the first 30 days

- Player segmentation based on deposits and profitability

- The goal was to provide data-driven insights that can improve onboarding, retention, and revenue strategies.

# 🛠 Tools & Technologies

- PostgreSQL → Data cleaning, SQL queries, exploratory data analysis

- Python (Jupyter Notebook, Pandas, NumPy) → Data manipulation & preprocessing

- Power BI → Dashboards & advanced data visualization

# 📂 Datasets Used

- Player details

- First deposit data

- First bet data

- Player activity logs

- Bonus cost data

# 📊 Key Analyses
## 1. Funnel & Conversion

- Funnel Stages: Registration → First Deposit → First Bet → Active in 30 days

- Findings:

 - 43% conversion from registration to deposit → main drop-off point

 - 81% conversion from deposit to first bet → strong intent among depositors

 - 91% bet within 30 days → high short-term engagement

## Insight: Improving onboarding incentives could significantly reduce the early drop-off.

## 2. Retention & Engagement

- Cohorted players by days active in the first 30 days (0–7, 8–15, etc.)

- Deposits proportional across cohorts → no single group over-contributing

- 90% players placed first bet on the same day as deposit → strong intent

## Engagement Insight: Short deposit-to-bet gaps indicate higher lifetime value.

## 3. Player Segmentation

- Top 10% players contributed ~49% of deposits → strong concentration of revenue.

- Deposit buckets show clustering:

- 0–100 deposits dominate in count (98k players)

- 101–500 deposits dominate in value

## Insight: Low depositors bring volume, but mid-level depositors drive revenue.

# 📈 Key Insights & Business Impact

- Major drop-off at deposit stage → need stronger incentives, trust-building.

- Retention closely tied to fast engagement → players who bet right after deposit are most valuable.

- Revenue concentration → top 10% of players drive half the deposits.

- First deposit amount is not a perfect profitability predictor → volume matters more.

📎 Resources
