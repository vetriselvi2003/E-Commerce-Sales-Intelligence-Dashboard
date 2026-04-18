# 📊 E-Commerce Sales Intelligence Dashboard

A multi-page Power BI dashboard analysing 50,000+ e-commerce transactions across 15 Indian cities, uncovering revenue patterns, profitability gaps, and operational insights.

**[🔗 Live Dashboard →](https://app.powerbi.com/your-link-here)**

---

## 📌 Problem Statement

E-commerce businesses generate massive transaction data but struggle to extract actionable insights across categories, regions, and customer segments. This project builds a complete BI solution that answers:
- Which categories drive revenue vs profit?
- Where are the geographic growth opportunities?
- How do discounts impact profitability?
- What does the festive season impact look like?

---

## 📊 Dashboard Pages

| Page | Focus | Key Visuals |
|------|-------|-------------|
| Executive Summary | Top-line KPIs + trends | Revenue trend, category bar, region map, payment donut |
| Category Intelligence | Product performance | Scatter plot, treemap, discount analysis, segment comparison |
| Geographic & Operations | Logistics + geography | City ranking, delivery heatmap, day-of-week patterns |

---

## 🗂️ Dataset

- **50,000 transactions** | Jan 2023 – Dec 2024
- **15 Indian cities** across 5 regions
- **8 product categories** | 25 sub-categories
- **Fields:** order date, city, state, region, category, revenue, profit, margin, payment method, customer segment, delivery days, return status, rating

---

## 🧮 DAX Measures Built

- Total Revenue, Total Profit, Total Orders
- Avg Order Value, Avg Profit Margin
- Return Rate %, Avg Rating, Avg Delivery Days
- Revenue 2023, Revenue 2024, YoY Growth %
- Revenue per Order

---

## 💡 Key Business Findings

| Finding | Insight |
|---------|---------|
| Electronics = 65% revenue, 12% margin | High volume, low profit — margin optimisation needed |
| Diwali season drives 4x order volume | Infrastructure scaling required in Oct–Nov |
| 30% discounts cut margin from 32% → 10% | Discount strategy needs cap at 15% |
| VIP customers (10%) = 28% of revenue | Loyalty program investment has high ROI |
| East region delivery = 2x South/West | Logistics partner gap — customer satisfaction risk |
| UPI = 38% of all payments | Digital-first payment infrastructure is now primary |
| Electronics return rate = 10.2% | Product description or quality mismatch issue |

---

## 🛠️ Tech Stack

- **Power BI Desktop** — dashboard design, DAX measures
- **SQL** — data aggregation and validation queries
- **Python** — dataset generation and preprocessing

---

## 📂 Files

```
ecommerce_bi/
├── ecommerce_sales.csv     # 50,000 row dataset
├── sql_queries.sql         # 15 analysis queries
├── POWER_BI_GUIDE.md       # Full step-by-step build guide
└── README.md
```

---

## 🚀 How to Reproduce

1. Download `ecommerce_sales.csv`
2. Open Power BI Desktop → Get Data → CSV
3. Follow `POWER_BI_GUIDE.md` step by step
4. Publish to Power BI Service for live link

---

*Built by Vetri Selvi B | Data Analytics Portfolio*
