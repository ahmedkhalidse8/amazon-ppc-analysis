# Amazon PPC Analysis Dashboard

This project analyzes Amazon PPC (Pay-Per-Click) advertising performance using Power BI to identify inefficiencies, optimize campaigns, and improve profitability.

---

##  Dashboard Preview

### 🔹 Executive Overview
![Executive Overview](visuals/Amazon%20PPC%20Performance%20Overview.png)

---

### 🔹 Campaign Performance Analysis
![Campaign Performance](visuals/Campaign%20Performance%20Analysis.png)

---

### 🔹 Keyword & Search Term Insights
![Keyword Insights](visuals/Keyword%20%26%20Search%20Term%20Insights.png)

---

## Project Overview

**Problem:** A $600K+ ad account had campaigns that looked normal on the surface but were quietly burning budget.

**Data note:** The repository contains a curated analysis dataset for reproducibility and portfolio review. The full Amazon Seller Central account data covered 50,000+ records and $600K+ in advertising activity.

**What I did:** Cleaned and analyzed 50,000+ Seller Central records in Python (Pandas), built a 3-view Power BI dashboard (Executive Overview, Campaign Performance, Keyword Insights) tracking ACOS, ROAS, CTR, and CPC.

**Key finding:** The account operated at approximately 94% ACOS, with several campaigns exceeding 100% ACOS. Search-term analysis identified non-converting queries consuming budget without generating sales.

**Result:** Findings directly informed pricing and campaign optimization decisions, reducing wasted ad spend.
---

## Project Structure

```
amazon-ppc-analysis/
│
├── dashboard/
│   └── amazon_ppc_dashboard.pbix
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   └── 02_analysis.ipynb
│
├── report/
│   └── insights.md
│
├── visuals/
│   ├── Amazon PPC Performance Overview.png
│   ├── Campaign Performance Analysis.png
│   └── Keyword & Search Term Insights.png
│
└── README.md
```

## How to View This Project

- **Don't have Power BI installed?** Check the `/visuals` folder for static screenshots of all three dashboard views.
- **Want to see the analysis process?** Open `/notebooks` — `01_data_cleaning.ipynb` and `02_analysis.ipynb` walk through the full data cleaning and analysis workflow.
- **Want the written summary?** See `/report/insights.md` for key findings in plain text.
---

## Key Insights

- ACOS ≈ 94% → extremely inefficient ad spend
- Broad campaigns generate sales but reduce profitability
- High spend on non-converting search terms
- Strong traffic but weak conversion performance

---

Example Analysis: High ACOS and Wasted Spend

One campaign-level example showed:

Impressions: 694,503

Clicks: 5,987

Ad Spend: $5,203.77

Ad Sales: $5,497.02

ACOS: 94.67%

ROAS: 1.06

Finding: Advertising spend consumed approximately 94.67% of attributed sales revenue, leaving limited revenue to cover product costs and other expenses.

Recommended action: Review search terms with spend but no attributed sales, add appropriate negative keywords, and adjust bids based on campaign and keyword performance.

Business objective: Reduce inefficient ad spend while preserving traffic and sales from high-performing search terms.

## Recommendations

- Reduce bids on high ACOS campaigns
- Add negative keywords for wasted spend
- Scale high-performing keywords
- Optimize product listing for better conversion

---

## 🛠 Tools Used

- Power BI
- Python (Pandas, NumPy)
- Jupyter Notebook

---

## Author

Ahmed Khalid  
JDV Enterprises LLC
