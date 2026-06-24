# 📊 Skill2Scale Data Analytics Internship Portfolio

### Augustine Jasmine Oyindeinyefa — Data Analyst & Business Intelligence Specialist
**Savvy Datalytics Solutions** | Q3 2025 (July – September)


## Overview

This repository contains the complete deliverables from the **Skill2Scale 4-Week Virtual Data Analytics Internship**, where I acted as a Data Analyst supporting **Linda Williams**, CEO of **Savvy Datalytics Solutions** — a fictional digital marketing consultancy based in Toronto, Canada.

Over four weeks, I cleaned and documented raw Q3 marketing data, built a 31-visual Power BI dashboard, produced trend and correlation analyses, modelled Q4 revenue projections, benchmarked competitors, and delivered a full suite of executive-facing reports — end-to-end, from raw CSV to board-ready insight.


## Repository Structure

```
Skill2Scale-Internship-Portfolio/
│
├── README.md                                         ← You are here
├── .gitignore
├── LICENSE
│
├── 01_week_1_data/
│   ├── documentataion/
│   │   ├──data_dictionary
│   │   ├──folder-sop
│   ├──notebooks/
│   │   ├──data_cleaning_process.md

│   ├── reports/                                      ← Weekly Data Insights Email to Linda                                    
│   └── README.md
│
├── 02_week_2_visualizati/
│   ├── dashboards/
│   │   ├── Marketing_Performance_Dashboard.pbix      ← Power BI dashboard (4 pages, 31 visuals)
│   │   └── Marketing_Performance_Dashboard.png       ← Screenshots
│   ├── presentations/
│   ├── reports/                                      ← 2-page Data Insights Report + Executive Summary
│   └── README.md
│
├── 03_week_3_business_intelligence/
│   ├── competitor_analysis/
│   │   └── Week3_Competitor_Comparison_Matrix.docx  ← 3-company benchmarking (landscape format)
│   ├── insight_memo_/
│   │   └── Week3_Insight_Memo_with_Projections.docx ← Trend, correlation, segmentation & Q4 projection
│   └── README.md
│
└── 04_week_4_executive_reporting/
    ├── presentations/
    │   └── Week4_Portfolio_Presentation.pptx         ← 8-slide portfolio deck
    ├── reflection/
    │   └── Week4_Reflection_Summary.docx             ← Personal growth reflection
    └── reports/
        ├── Week4_Business_Optimization_Proposal.docx ← Automated reporting pipeline proposal
        └── Week4_End_of_Month_Analytics_Report.docx  ← Full Q3 KPI summary & MoM growth analysis
```


## Q3 2025 — Key Results at a Glance

| Metric | Q3 Value |
|---|---|
| **Total Revenue** | $2,422,384.74 |
| **Total Ad Spend** | $713,478.15 |
| **Overall ROI** | **239.5%** |
| **Total Clicks** | 2,246,443 |
| **Total Conversions** | 119,486 |
| **Conversion Rate** | 5.32% |
| **Revenue per $ Spent** | $3.40 |
| **Cost per Conversion** | $5.97 |

> All five channels maintained ROI above 212%. No underperforming channel in the Q3 mix.


## Week-by-Week Deliverables

### Week 1 — Data Foundations & Organisation
`01_week_1_data_foundations/`

**Goal:** Establish analytical systems, clean raw data, and create foundational documentation.

**Deliverables:**
- ✅ Cleaned dataset audit across all three files (Campaign_Data_Q3, Ad_Spend_JulySept, Leads_Report)
- ✅ Data Dictionary — column definitions and variable descriptions
- ✅ Folder & File Management SOP — naming conventions and storage rules
- ✅ Exploratory Summary — descriptive statistics, total revenue, ad spend, ROI, top channel
- ✅ Weekly Data Insights Email to Linda Williams

**Key Finding:** TikTok Ads was the top-performing channel at 259.6% ROI and $538,986 in Q3 revenue.


### Week 2 — Visualization & Insight Communication
`02_week_2_visualization_dashboard/`

**Goal:** Translate numbers into clear, actionable visuals for business decision-making.

**Deliverables:**
- ✅ **Marketing Performance Dashboard** — Power BI, 4 pages, 31 visuals:
  - Page 1: Main Dashboard — 6 KPI cards, Top 5 Campaigns by ROI, Revenue by Channel, Monthly Revenue trend, Donut chart, 3 slicers
  - Page 2: Trend Analysis — 5 trend lines + Q4 Projection KPI card
  - Page 3: Correlation Analysis — 3 scatter charts (Spend vs Revenue, Spend vs Conversions, Clicks vs Conversions)
  - Page 4: Segmentation — 4 visuals using `SWITCH(TRUE())` DAX logic
- ✅ 2-page Data Insights Report
- ✅ Executive Summary paragraph for stakeholders

**DAX highlights:** Custom `Performance_Segment` column using `SWITCH(TRUE())` with 300%/150% ROI thresholds; `ROI%`, `Conversion_Rate`, and `Cost_per_Conversion` measures.


### Week 3 — Business Intelligence & Predictive Insights
`03_week_3_business_intelligence/`

**Goal:** Identify trends, model correlations, segment campaigns, project Q4 revenue, and benchmark against competitors.

**Deliverables:**
- ✅ Trend Analysis — August peak at $865,736 revenue (+8.4% MoM); September efficiency held despite lower spend
- ✅ Correlation Analysis across three relationships:
  - Ad Spend → Revenue: **Strong Positive**
  - Ad Spend → Conversions: **Moderate Positive**
  - Clicks → Conversions: **Weak** ← most impactful finding
- ✅ Campaign Segmentation — all 5 campaigns in Mid Performer band (150–299% ROI); zero low performers
- ✅ Q4 Revenue Projection — Conservative $2.62M | Optimistic $2.82M
- ✅ **Competitor Comparison Matrix** — Tech Savvy Solutions ranked #1 in ROI (239.5%) and cost efficiency ($5.97/conversion)
- ✅ **Strategic Insight Memo with Projections**

**Most significant finding:** The weak Clicks → Conversions correlation. High click volume does not reliably produce conversions — shifting Q4 focus from CPC to CRO is the highest-impact recommendation.


### Week 4 — Executive Reporting & Portfolio Compilation
`04_week_4_execuive_reporing/`

**Goal:** Deliver professional-grade analytics output and compile the full portfolio.

**Deliverables:**
- ✅ **End-of-Month Analytics Report** — full Q3 KPI dashboard, MoM growth table, channel and campaign rankings, Q4 outlook
- ✅ **Business Optimization Proposal** — 5-phase Automated Marketing Intelligence Pipeline replacing manual CSV workflows with Power BI Service + API connections + Power Automate alerts
- ✅ **Reflection Summary** — personal reflection on analytical growth and professional development
- ✅ **Portfolio Presentation** — 8-slide deck covering project overview, Q3 results, dashboard structure, trend/correlation findings, competitive positioning, and Q4 strategy


## Most Significant Analytical Finding

> **Clicks do not reliably predict conversions.**

With 2,246,443 total Q3 clicks and a 5.32% conversion rate, the data shows that the Clicks → Conversions relationship across the dataset is weak. Channels generating high click volume were not consistently the strongest converters. This finding directly shifts the Q4 recommendation from "generate more clicks" to "improve conversion quality" — a meaningful difference in strategy and budget allocation.


## Tools & Technologies

| Category | Tool |
|---|---|
| Business Intelligence | Microsoft Power BI Desktop |
| Data Modelling | DAX (SWITCH/TRUE, CALCULATE, DIVIDE, RELATED) |
| Spreadsheet Analysis | Microsoft Excel |
| Document Production | Microsoft Word (.docx) |
| Presentation | Microsoft PowerPoint (.pptx) |
| Version Control | GitHub |



## Dashboard

> **File:** `02_week_2_visualizati/dashboards/Marketing_Performance_Dashboard.pbix`
>
> Open in Power BI Desktop to interact with all 4 pages and 31 visuals.


## About the Analyst

**Augustine Jasmine Oyindeinyefa**
Data Analyst & Business Intelligence Specialist | Savvy Datalytics Solutions
BSc Computer Science — University of Africa, Toru-Orua

Specialisations: Excel · Power BI · DAX · Data Cleaning · Business Reporting · Predictive Insights · Explainable AI


*Skill2Scale Virtual Data Analytics Internship | Q3 2025 | Savvy Datalytics Solutions*
