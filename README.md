# Retail Sales Performance Dashboard (Excel)

An interactive Excel dashboard built to analyze one year of retail sales performance across regions, product categories, and customer satisfaction — turning 1,000 raw transaction records into decision-ready insights for merchandising and regional planning teams.

## Business Problem

Retail leadership needed a single view to answer three recurring questions:

1. Which regions and categories are driving revenue, and which are underperforming?
2. How does demand shift month to month, and where are the seasonal peaks?
3. Is customer satisfaction holding steady as sales volume grows?

This project builds a self-service Excel dashboard so stakeholders can answer these questions without pulling a new report every time.

## Dataset

| Detail | Description |
|---|---|
| Source file | `Data_Analytics_Project_Dataset.xlsx` |
| Records | 1,000 orders |
| Time period | January – December 2025 |
| Granularity | One row per order |

Fields: `OrderID`, `OrderDate`, `Region` (North / South / East / West), `Category` (Electronics / Furniture / Office Supplies), `Product` (9 SKUs), `UnitsSold`, `UnitPrice`, `Revenue`, `CustomerSatisfaction` (1–5 rating), `Month`.

## Tools & Techniques

- Microsoft Excel — data cleaning, structured tables, formulas (`SUMIFS`, `AVERAGEIFS`, `COUNTIFS`)
- PivotTables & PivotCharts — dynamic slicing by region, category, and month
- Slicers & Timelines — interactive filtering for a self-service dashboard experience
- Conditional Formatting — quick visual flags for high/low performers
- Data Validation — clean, consistent categorical inputs

## Dashboard Overview

The dashboard consolidates the full dataset into four linked views:

- **Executive Summary** — headline KPIs at a glance (revenue, units, orders, satisfaction)
- **Regional Performance** — revenue and order volume by region
- **Category & Product Mix** — revenue breakdown by category and top/bottom SKUs
- **Monthly Trend** — seasonality and month-over-month revenue movement

<img src="https://github.com/user-attachments/assets/f52486d2-a690-41c0-960e-dd484939c005" width="600" alt="Dashboard"/>
<center>
    <img src=">
</center>


## Key Insights

**Headline KPIs**
- **Total Revenue:** ₹1,03,23,697 across 1,000 orders
- **Units Sold:** 13,321 units (avg. 13.3 units/order)
- **Average Customer Satisfaction:** 4.01 / 5
- **Average Order Value:** ₹10,324

**Regional Performance**
| Region | Revenue | Share |
|---|---|---|
| South | ₹29,10,054 | 28.2% |
| North | ₹25,93,097 | 25.1% |
| West | ₹24,63,350 | 23.9% |
| East | ₹23,57,197 | 22.8% |

South leads all regions, generating ~5 percentage points more revenue share than the lowest-performing region (East) — a candidate area for a targeted regional promotion.

**Category Mix**
| Category | Revenue | Share |
|---|---|---|
| Electronics | ₹36,33,268 | 35.2% |
| Office Supplies | ₹35,12,480 | 34.0% |
| Furniture | ₹31,77,950 | 30.8% |

Category revenue is well balanced (within a ~4-point spread), showing no single category over-indexes — a healthy, diversified product mix.

**Top & Bottom Products by Revenue**
1. Laptop — ₹12,91,249
2. Pen — ₹12,68,985
3. Tablet — ₹12,62,283
- Lowest: Chair — ₹9,36,739

Laptops and Tablets (high unit price, Electronics) and Pens (high volume, Office Supplies) prove that **both premium and high-frequency items** are meaningful revenue drivers — worth reflecting in inventory and marketing spend.

**Seasonality**
- **Peak month:** January (₹10,00,639)
- **Second peak:** May (₹10,87,348) — actually the highest single month
- **Lowest month:** December (₹7,21,309)

Revenue dips notably in December despite the holiday season, which is worth flagging to merchandising for further investigation (e.g., stock-outs, promotional timing).

**Customer Satisfaction**
- Average satisfaction sits at **4.01/5** and remains stable across regions and categories — sales growth has not come at the cost of customer experience.

## Recommendations

- Investigate the December revenue dip — check for stock availability and promotional calendar gaps.
- Replicate South region's playbook (pricing, promotions, assortment) in East, the lowest-performing region.
- Continue investment in Electronics and Office Supplies, the two strongest categories by revenue.

## Repository Structure

```
retail-sales-dashboard/
├── README.md
├── Data_Analytics_Project_Dataset.xlsx   # raw data + PivotTables + dashboard
└── assets/
    └── dashboard_overview.png            # dashboard screenshot(s)
```


## Skills Demonstrated

`Excel` · `PivotTables & PivotCharts` · `Data Cleaning` · `Dashboard Design` · `KPI Definition` · `Business Storytelling`

---
*Author: Deepti R · 
