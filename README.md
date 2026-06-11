# Customer Behavior Analytics

A real-world-ready, end‑to‑end data analytics project showcasing the full workflow: data ingestion, exploration, cleaning, SQL analysis, interactive dashboards, and executive reporting.

---

## 🧭 Overview

This project demonstrates a complete analytics lifecycle—starting with a raw CSV and culminating in a clear, executive‑ready presentation. It highlights practical skills in data wrangling (Python), scalable querying (SQL Server), storytelling dashboards (Power BI), and concise reporting (Gamma).

**Objective:** Identify trends in shopping behavior and revenue performance, surface actionable insights, and communicate them effectively to stakeholders.

---

## 📂 Dataset

* **Format:** CSV
* **Size:** 3,900 rows × 18 columns
* **Description:** Customer shopping behavior across categories (e.g., sales performance, purchase frequency, product mix, channel attribution).
* **Target Outcomes:**

  * Spot demand and seasonality trends
  * Segment customers by value and engagement
  * Diagnose discount/margin trade‑offs
  * Inform experiments and commercial levers

---

## 🛠️ Tools & Technologies

| Category      | Tools                                       |
| ------------- | ------------------------------------------- |
| Programming   | Python (pandas, NumPy, matplotlib, seaborn) |
| Database      | SQL Server                                  |
| Visualization | Power BI                                    |
| Reporting     | Gamma (final presentation)                  |
| Environment   | Jupyter Notebook                            |

---

## 🚀 Project Workflow

1. **Load & Inspect**

   * Read CSV with `pandas`, validate schema, enforce data types
   * Basic sanity checks (row/column counts, unique keys)

2. **Exploratory Data Analysis (EDA)**

   * Summary stats, distributions, and correlations
   * Univariate & bivariate visuals (histograms, box plots, heatmaps)
   * Identify skew, outliers, and potential feature leakage

3. **Data Cleaning**

   * Handle missingness
   * Deduplicate records, standardize units and formats
   * Create derived features

4. **SQL Analysis (on cleaned data)**

   * Load to SQL Server (staging → core)
   * Aggregations, joins, filters for KPI drill‑downs
   * Parameterized queries for time windows and segments

5. **Power BI Dashboard**

   * KPIs (Revenue, AOV, Orders, Conversion)
   * Trend & seasonality views, category/product breakdowns
   * Customer segments with drill‑through (e.g., Loyal, At‑Risk)
   * Filters for date range, channel, category, and promotion

6. **Reporting**

   * Executive summary in Gamma
   * Insight callouts with recommended actions and expected impact
---

## 📊 Power BI Highlights

* KPI cards with YoY/DoD deltas and conditional formatting
* Decomposition tree for revenue drivers (price, units, mix)
* Cohort chart for repeat behavior
* Segment pages: **Loyal**, **New**, **At‑Risk** with drill‑through to customers and orders
* Bookmark‑driven narratives for exec walk‑through

---

## 🧾 Key Results & Recommendations

* **Boost Subscriptions:** Promote exclusive benefits to raise repeat purchase rate and stabilize revenue.
* **Loyalty Program:** Incentivize repeat buyers (tiered rewards, early access) to grow the **Loyal** segment.
* **Discount Policy Review:** Tighten discount governance; pair promotions with attach‑rate or basket‑size goals to protect margin.
* **Category Focus:** Prioritize high‑elasticity categories during peak periods; reduce clutter in low‑velocity SKUs.
* **Experimentation:** A/B test thresholds (free shipping, bundle offers) and measure lift in conversion and AOV.

---


## 👤 Author

**Name:** Gopal Amle  
**Email:** gopsamle@gmail.com  
**LinkedIn:** [https://www.linkedin.com/in/gopal-amle-45274a231/](https://www.linkedin.com/in/gopal-amle-45274a231/)


---

