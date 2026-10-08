# 🛒 Retail Analytics Dashboard – Sales & Performance Insights

> **Tools:** Power BI | Excel | Power Query | DAX | Data Visualization  
> **Domain:** Retail | Sales Analytics | Business Intelligence

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Excel](https://img.shields.io/badge/Tool-Excel-green)
![Power Query](https://img.shields.io/badge/Tool-Power%20Query-blue)
![DAX](https://img.shields.io/badge/Language-DAX-orange)
![Domain-Retail](https://img.shields.io/badge/Domain-Retail-purple)

---

## 🧩 Project Overview

This project analyzes a **verified 600-record retail transaction dataset** to understand sales performance across products, stores, payment methods, time periods, and days of the week.

The analysis was designed to transform transaction-level retail data into **actionable business insights** using Power BI-style interactive visualizations and KPI reporting.

The dashboard evaluates:

- Product revenue performance
- Store-level revenue performance
- Payment method distribution
- Revenue by time of day
- Revenue by day of week
- Overall transaction, revenue, and unit-sales KPIs
- Business opportunities and recommended actions

---

## 🎯 Project Objectives

### 1. Analyze Product Performance
Identify the highest- and lowest-performing products based on revenue contribution.

### 2. Evaluate Store Performance
Compare revenue across all 10 stores and identify performance gaps between leading and underperforming locations.

### 3. Understand Payment Behavior
Analyze revenue contribution across debit card, credit card, cash, online, and gift card transactions.

### 4. Identify Time-Based Sales Patterns
Determine the strongest and weakest revenue periods across morning, afternoon, and evening.

### 5. Analyze Weekly Sales Trends
Compare revenue across the seven days of the week and identify peak shopping days.

### 6. Develop Business Recommendations
Translate the analysis into recommendations for inventory, staffing, promotions, store operations, and payment strategy.

---

## 📂 Dataset Overview

The dashboard is based on a **600-record verified retail transaction dataset**.

| Metric | Value |
|---|---:|
| Total Transactions | **600** |
| Total Revenue | **₹707,221.10** |
| Total Units Sold | **3,344** |
| Average Transaction Value | **₹1,179** |
| Number of Products | **7** |
| Number of Stores | **10** |
| Payment Methods | **5** |
| Time Periods | **3** – Morning, Afternoon, Evening |
| Days Analyzed | **7** – Monday to Sunday |

> **Dataset status:** ✅ Verified and aligned with the 600-record dataset.

---

## ❓ Problem Statement

Retail businesses need to understand not only how much they sell, but also **what products sell, where revenue is generated, how customers pay, and when demand is highest**.

This project addresses the following business questions:

- Which products generate the highest revenue?
- Which stores are performing above or below the overall store average?
- What is the revenue contribution of each payment method?
- Which time of day generates the most revenue?
- Which days of the week generate the strongest sales?
- Where are the largest performance gaps?
- Which areas should management prioritize for improvement?
- How can staffing, inventory, promotions, and store operations be optimized?

---

## 🧾 Analytical Dimensions

The analysis focuses on the following major dimensions:

| Dimension | Analysis Focus |
|---|---|
| Product | Revenue ranking and product contribution |
| Store | Store revenue ranking and performance gap |
| Payment Method | Revenue share and transaction distribution |
| Time of Day | Morning, afternoon, and evening revenue |
| Day of Week | Weekly revenue patterns |
| Transaction | Total transaction count and average transaction value |
| Units | Total units sold |
| Revenue | Total and comparative revenue performance |

---

## 🧹 Data Preparation & Validation

The project uses a **600-record verified dataset** as the basis for dashboard analysis.

The preparation process focused on:

1. **Dataset Verification**  
   Confirmed that the analytical dataset contains 600 transactions.

2. **Data Alignment**  
   Ensured the dashboard metrics and visualizations were aligned with the verified dataset.

3. **Metric Validation**  
   Validated key metrics including total revenue, total units, transaction count, product count, store count, and payment method count.

4. **Category Analysis**  
   Organized transaction data into product, store, payment, time-of-day, and day-of-week dimensions.

5. **Dashboard Analysis**  
   Built analytical views to compare performance and identify business opportunities.

---

# 📊 Analysis & Visualizations

<img width="1153" height="658" alt="image" src="https://github.com/user-attachments/assets/310abc97-89d3-4a5e-b775-0b96822af04e" />


## 1️⃣ Product Performance Analysis

### Product Revenue Ranking

| Rank | Product | Revenue | % of Total | Performance |
|---:|---|---:|---:|---|
| 🥇 1 | **Phone** | ₹121,774.10 | 17.2% | ⭐ Top Performer |
| 🥈 2 | **Monitor** | ₹114,606.96 | 16.2% | ⭐ Strong |
| 🥉 3 | **Printer** | ₹101,254.93 | 14.3% | ⭐ Strong |
| 4 | **Chair** | ₹100,579.20 | 14.2% | ✓ Good |
| 5 | **Desk** | ₹95,007.42 | 13.4% | ✓ Good |
| 6 | **Tablet** | ₹88,347.60 | 12.5% | ✓ Moderate |
| 7 | **Laptop** | ₹85,650.89 | 12.1% | ⚠️ Lowest |

### Key Insights

<img width="1158" height="650" alt="image" src="https://github.com/user-attachments/assets/9acbd451-26eb-4678-9d78-2751ef351a1c" />


- **Phone, Monitor, and Printer** are the top three revenue-generating products.
- Together, the top three products contribute approximately **47.7% of total revenue**.
- **Laptop** is the lowest-performing product at **12.1% of revenue**.
- No single product contributes more than 18%, indicating a relatively balanced product mix.

### Business Actions

| Priority | Recommended Action |
|---|---|
| Immediate | Focus promotional activity on Phone, Monitor, and Printer |
| Week 1 | Review Laptop pricing and competitive positioning |
| Week 2 | Test Laptop + Monitor and other bundle offers |
| Ongoing | Track weekly product revenue performance |

---

## 2️⃣ Store Performance Analysis

### Store Revenue Ranking

| Rank | Store | Revenue | % of Total | Gap vs. Leader |
|---:|---|---:|---:|---:|
| 🥇 1 | **S9** | ₹87,997.41 | 12.4% | Leader |
| 🥈 2 | **S7** | ₹81,813.00 | 11.6% | -7% |
| 🥉 3 | **S8** | ₹78,404.20 | 11.1% | -11% |
| 4 | **S1** | ₹76,384.75 | 10.8% | -13% |
| 5 | **S4** | ₹73,840.06 | 10.4% | -16% |
| 6 | **S3** | ₹68,404.07 | 9.7% | -22% |
| 7 | **S5** | ₹64,588.13 | 9.1% | -27% |
| 8 | **S2** | ₹64,069.19 | 9.1% | -27% |
| 9 | **S10** | ₹57,856.03 | 8.2% | -34% |
| 🔟 | **S6** | ₹53,864.26 | 7.6% | -39% |

### Key Insights

- **S9** is the highest-revenue store at **₹87,997.41**.
- **S6** is the lowest-revenue store at **₹53,864.26**.
- The revenue difference between S9 and S6 is approximately **₹34,133**.
- The analysis identifies a significant performance gap that should be investigated through operations, staffing, location, inventory, and management factors.

### Business Actions

| Priority | Recommended Action |
|---|---|
| Immediate | Benchmark S9's operational practices |
| Immediate | Diagnose the causes of S6's lower performance |
| Short Term | Roll out effective S9 practices to lower-performing stores |
| Medium Term | Establish store-level performance targets and monitor weekly |

---

## 3️⃣ Payment Method Analysis

### Revenue by Payment Method

| Rank | Payment Method | Revenue | Revenue Share |
|---:|---|---:|---:|
| 🥇 1 | **Debit Card** | ₹159,895.88 | 22.6% |
| 🥈 2 | **Credit Card** | ₹151,214.01 | 21.4% |
| 🥉 3 | **Cash** | ₹132,683.74 | 18.8% |
| 4 | **Online** | ₹132,231.49 | 18.7% |
| 5 | **Gift Card** | ₹131,195.98 | 18.5% |

### Key Insights

- **Debit Card** is the largest individual payment method at **22.6%**.
- **Credit Card** follows closely at **21.4%**.
- Debit and credit card transactions together account for approximately **44% of revenue**.
- Cash remains significant at **18.8%**.
- Online and gift card payments each contribute approximately 18–19% of revenue.

### Business Actions

- Monitor debit and credit card payment reliability.
- Ensure payment terminals and POS systems operate consistently.
- Review cash-handling procedures.
- Monitor payment-method trends by store.
- Evaluate opportunities to encourage faster digital payment adoption.

---

## 4️⃣ Time of Day Analysis

### Revenue by Time Period

| Time Period | Revenue | % Share | Performance |
|---|---:|---:|---|
| 🌅 Morning | ₹169,019.81 | 24.0% | 📉 Lowest |
| ☀️ Afternoon | ₹254,901.10 | 36.0% | 📈 Good |
| 🌙 Evening | ₹283,300.19 | 40.0% | 🔥 Peak |

### Key Insights

- **Evening** is the strongest revenue period, contributing **40%**.
- **Afternoon** contributes **36%**.
- **Morning** contributes **24%**, making it the weakest period.
- Evening demand should be considered when planning staffing and inventory availability.

### Staffing Recommendation

| Time Period | Suggested Staffing Allocation |
|---|---:|
| Morning | 25% |
| Afternoon | 35% |
| Evening | 40% |

> These percentages are recommendations based on the revenue distribution and should be validated against actual staffing requirements.

---

## 5️⃣ Day of Week Analysis

### Revenue by Day

| Rank | Day | Revenue | % Share | Trend |
|---:|---|---:|---:|---|
| 🥇 1 | **Tuesday** | ₹123,388.42 | 17.4% | 📈 Peak |
| 🥈 2 | **Thursday** | ₹122,934.22 | 17.4% | 📈 Peak |
| 🥉 3 | **Friday** | ₹109,693.77 | 15.5% | ✓ Good |
| 4 | Other Days | ~₹100K average | ~14% each | — |

### Key Insights

- **Tuesday and Thursday** are the strongest identified revenue days.
- Together, Tuesday and Thursday contribute approximately **34.8% of weekly revenue**.
- Friday remains a strong sales day at **15.5%**.
- The available analysis identifies potential weekly patterns that can support staffing and promotional planning.

### Business Actions

| Area | Recommendation |
|---|---|
| Staffing | Increase coverage around Tuesday–Thursday demand |
| Promotions | Use targeted promotions during lower-revenue periods |
| Inventory | Prepare inventory ahead of stronger demand periods |
| Monitoring | Track weekly trends to validate recurring patterns |

---

# 📌 Consolidated KPI Summary

| KPI | Result |
|---|---:|
| **Total Transactions** | 600 |
| **Total Revenue** | ₹707,221.10 |
| **Total Units Sold** | 3,344 |
| **Average Transaction Value** | ₹1,179 |
| **Average Revenue per Store** | ₹70,722 |
| **Top Product** | Phone – ₹121,774.10 |
| **Top Store** | S9 – ₹87,997.41 |
| **Top Payment Method** | Debit Card – 22.6% |
| **Peak Time Period** | Evening – 40.0% |
| **Top Revenue Day** | Tuesday – 17.4% |

---

# 💡 Key Business Insights

### 🏆 Product Performance
The top three products — **Phone, Monitor, and Printer** — generate approximately **47.7% of total revenue**, making them important products for inventory planning and promotional campaigns.

### 🏪 Store Performance
**S9** is the leading store, while **S6** is the lowest-performing store. The difference highlights an opportunity to investigate operational and management practices across locations.

### 💳 Payment Behavior
Card payments represent approximately **44% of total revenue**, with debit cards contributing the largest individual share.

### 🌙 Time-Based Demand
The **evening period generates 40% of revenue**, making it the primary period for staffing, inventory availability, and cross-selling opportunities.

### 📅 Weekly Demand
**Tuesday and Thursday** are the strongest identified revenue days, suggesting an opportunity to align staffing and promotional activity with weekly demand patterns.

---

# 🎯 Business Recommendations

| Priority | Area | Recommendation |
|---|---|---|
| 🔴 1 | Store Performance | Benchmark S9 and investigate the S9–S6 performance gap |
| 🟠 2 | Product Strategy | Review Laptop pricing, inventory, placement, and bundling |
| 🟠 3 | Time Optimization | Optimize staffing around evening demand |
| 🟡 4 | Promotions | Use targeted promotions to improve weaker periods |
| 🟡 5 | Payment Strategy | Maintain reliable card processing and monitor payment trends |
| 🟢 6 | Continuous Monitoring | Review store, product, payment, and time-based KPIs regularly |

---

# 📊 Recommended Power BI Visualizations

| Analysis | Recommended Visual | Purpose |
|---|---|---|
| Product Revenue | Horizontal Bar Chart | Compare revenue across 7 products |
| Store Revenue | Bar Chart | Rank all 10 stores |
| Payment Methods | Donut Chart | Show revenue share by payment type |
| Time of Day | Column/Bar Chart | Compare morning, afternoon, and evening |
| KPI Summary | KPI Cards | Display revenue, transactions, units, and average transaction value |

### Dashboard Preview

Add the exported dashboard screenshot to your repository and update the path below:

```markdown
![Retail Analytics Dashboard](Retail_Analytics_Dashboard.png)
)
```

---

# 📈 90-Day Target Framework

The source analysis proposes the following target framework for measuring improvement:

| Metric | Current | Target | Improvement |
|---|---:|---:|---:|
| Total Revenue | ₹707,221 | ₹785,000 | +11% |
| Store Performance Gap | 39 points | 15 points | -24 points |
| Morning Revenue Share | 24% | 28% | +4% |
| Laptop Revenue Share | 12.1% | 13.5% | +1.4% |
| Average Store Revenue | ₹70,722 | ₹78,500 | +11% |
| Labor Efficiency | — | +15% | Savings target |

> The targets above are **proposed business targets from the analysis**, not historical results.

---

# 🗓️ Implementation Roadmap

### Week 1
- Review the dashboard and KPI results.
- Audit the highest-performing store, S9.
- Investigate the lowest-performing store, S6.
- Review Laptop pricing and competitive positioning.
- Check debit card payment reliability.

### Week 2
- Document effective S9 operating practices.
- Test targeted morning promotions.
- Review staffing allocation by time of day.
- Test Laptop + Monitor bundling.
- Review payment-method performance.

### Weeks 3–4
- Begin applying successful practices to lower-performing stores.
- Monitor morning revenue.
- Measure product bundle performance.
- Track Tuesday–Thursday performance.
- Conduct weekly dashboard reviews.

### Month 2
- Measure improvement in S6 and other lower-performing stores.
- Adjust promotions based on observed results.
- Review weekend staffing and operating patterns.
- Analyze customer feedback where available.

### Month 3
- Evaluate the impact of implemented changes.
- Measure return on recommendations.
- Compare actual performance against targets.
- Define the next improvement cycle.

---

# 🧠 Conclusion

This Retail Analytics project demonstrates how transaction-level data can be transformed into **business-focused insights using Power BI, Excel, Power Query, and DAX**.

The analysis highlights several important opportunities:

- **Phone, Monitor, and Printer** are the strongest product revenue contributors.
- **S9** is the top-performing store, while **S6** requires further investigation.
- **Debit Card** is the leading payment method.
- **Evening** is the strongest revenue period.
- **Tuesday and Thursday** are the strongest identified revenue days.
- Store performance, product strategy, staffing, and payment optimization provide opportunities for further improvement.

The project demonstrates the complete analytical journey from **verified transaction data → KPI analysis → interactive visualization → business insights → actionable recommendations**.

---

## 📁 Project Structure

A suggested GitHub repository structure:

```text
Retail-Analytics-PowerBI/
│
├── README.md
│
├── data/
│   └── Retail-Store-Transactions.xlsx
│
├── dashboards/
│   └── dashboard_screenshots/
│       └── Retail_Analytics_Dashboard.png
│
├── powerbi/
│   └── Retail_Analytics_Dashboard.pbix
│
└── documentation/
    └── Retail_Analytics_Analysis.md
```

---

## 👩‍💻 Author

**Anwar Basha**  
*Data Analyst | Power BI | Business Analytics*

- 🌐 GitHub: `[https://github.com/anwarbasha188-pixel]`
- 💼 LinkedIn: `[[LinkedI](https://www.linkedin.com/in/anwar-basha1/?)]`
- 📧 Email: `[anwarbasha188@gmail.com]`

---

## 📚 Tags

`#PowerBI` `#DataAnalysis` `#RetailAnalytics` `#BusinessIntelligence`  
`#DAX` `#PowerQuery` `#Excel` `#DataVisualization` `#SalesAnalytics`
