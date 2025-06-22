## Power-Bi-Project
# 📊 Global Superstore Command Center – Power BI Dashboard

> An Interactive Business Intelligence Dashboard for Sales & Profit Optimization  
> 🛠️ Built with Power BI using DAX, star schema modeling, and advanced visualizations

---

## 🧾 Project Overview

This project presents a fully interactive **Power BI dashboard** developed for **Global Superstore**, a multinational retailer. The goal is to empower business leaders with **data-driven insights** on revenue growth, margin optimization, logistics performance, and customer segmentation across multiple regions and product categories.

🔍 Based on real-world enterprise challenges and requirements.

---

## 🎯 Business Objectives

1. **📈 Revenue Growth** – Identify under-penetrated regions and product lines.
2. **💰 Margin Improvement** – Optimize discount strategies without eroding profits.
3. **🚚 Operational Efficiency** – Evaluate logistics performance and cost-effectiveness.
4. **👥 Customer Profiling** – Pinpoint high-LTV segments (e.g., Consumer, Corporate, Home Office).

---

## ❓ Key Questions Answered

- Which categories and regions underperform in profit despite high sales?
- How much discount is “too much” before profitability is compromised?
- Is expedited shipping generating a return on investment?
- What regions/cities show frequent returns or delays?
- What seasonal trends affect inventory and promotion planning?

---

## 🧠 Features & Insights

### ✅ KPIs Tracked
- **Total Sales, Total Profit**
- **Profit Margin (%)**
- **Average Discount**
- **YOY Growth Rates**
- **Discount-Profit Correlation**
- **Average Order Lead Time**

### 📊 Visualizations
| Page                 | Key Visuals                                                                      |
|----------------------|----------------------------------------------------------------------------------|
| **Dashboard**        | KPI Cards, Trendlines, Profit Heatmap by Region                                 |
| **Category Insights**| Bar/Drill Charts: Category → Sub-category                                        |
| **Discount Impact**  | Scatter Plot: Discount % vs Profit Margin %                                      |
| **Shipping Analysis**| Box & Whisker: Lead Time by Region & Ship Mode                                   |
| **Geo View**         | Filled Map: Profit Margin by Country/City                                        |
| **Segment Insights** | Slicer/Small Multiples: Consumer vs Corporate vs Home Office                     |

---

## 🗃️ Data & Model Design

- **Tables Used**: `Orders`, `Returns`, `People`
- **Time Period**: Jan 2016 – Dec 2019
- **Data Model**: Star schema with dimension tables (Date, Customer, Product, Shipping)

### 🔧 DAX Measures
- `Total Sales`, `Total Profit`, `Profit Margin %`
- `Avg. Discount`, `YOY Sales/Profit Growth`
- `Lead Time = DATEDIFF(Order Date, Ship Date, DAY)`
- `Discount to Profit Correlation`

---

## 🏁 Success Criteria

✅ Full interactivity (cross-filtering, slicers, drill-through)  
⚡ Loads in < 5 seconds  
💡 Surfaces at least 3 non-obvious, actionable insights  
📽️ Delivered with a concise 5-slide executive summary (Optional presentation)

---

## 🧩 Folder Structure

```bash
📁 Global-Superstore-PowerBI/
├── 📄 Problem_Statement_v1.pdf     # Project background and business goals
├── 📊 Global Superstore Command Center.pbix
├── 📄 README.md                    # You're reading it!

