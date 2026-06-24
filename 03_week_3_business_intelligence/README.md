# Week 3 — Business Intelligence & Predictive Insights

**Skill2Scale Virtual Data Analytics Internship | Q3 2025**
**Analyst:** Augustine Jasmine Oyindeinyefa — Data Analyst & Business Intelligence Specialist | Savvy Datalytics Solutions
**Client:** Linda Williams — Savvy Daalytics Solutions

## Week 3 Objective

To demonstrate analytical depth by moving beyond descriptive statistics into trend identification, correlation modelling, campaign segmentation, predictive projection, and competitive benchmarking — then communicating all findings in a concise strategic memo.


## Files in This Folder

| File | Description |
|---|---|
| `Week3_Competitor_Comparison_Matrix.docx` | Side-by-side benchmarking of Savvy Daalytics Solutions against two competitors across 15+ metrics |
| `Week3_Insight_Memo_with_Projections.docx` | Strategic memo covering trend analysis, correlation findings, segmentation, and Q4 revenue projection |


## Tasks Completed

### 1. Trend Analysis
Examined monthly performance patterns across July, August, and September 2025 using the primary Campaign_Data_Q3_Cleaned dataset.

| Month | Revenue | Ad Spend | ROI | Conversions |
|---|---|---|---|---|
| July | $798,976 | $244,641 | 226.6% | 38,228 |
| **August ★** | **$865,736** | $249,820 | **246.5%** | **42,108** |
| September | $757,673 | $219,017 | 245.9% | 39,150 |

**Key finding:** August was the peak month — $865,736 in revenue and 246.5% ROI, representing +8.4% MoM revenue growth. September's lower revenue was matched by proportionally lower spend, meaning ROI efficiency was nearly unchanged. This confirmed a spend reduction, not a performance deterioration.


### 2. Correlation Analysis
Tested three relationships across the Q3 dataset to understand what actually drives conversions and revenue.

| Relationship | Correlation Strength | Business Implication |
|---|---|---|
| Ad Spend → Revenue | **Strong Positive** | Budget investment reliably produces proportional revenue returns |
| Ad Spend → Conversions | **Moderate Positive** | Spend increases lift conversions but with diminishing efficiency at higher ranges |
| Clicks → Conversions | **Weak** | High click volume does not reliably predict conversion volume |

**Most significant finding:** The weak Clicks → Conversions relationship. With 2,246,443 total Q3 clicks producing only a 5.32% conversion rate, generating more clicks without improving targeting or landing page quality will not move the conversion needle. This is the finding most likely to change Q4 budget and strategy decisions.


### 3. Campaign Segmentation
Campaigns were segmented into performance tiers using ROI thresholds consistent with the Power BI dashboard's SWITCH(TRUE()) DAX logic.

| Segment | ROI Threshold | Q3 Campaigns |
|---|---|---|
| 🟢 High Performer | ≥ 300% ROI | None — Holiday Promo (254.3%) and Brand Awareness (248.6%) are closest |
| 🟡 Mid Performer | 150% – 299% ROI | All 5 campaigns fall here |
| 🔴 Low Performer | < 150% ROI | None |

**Notable:** The complete absence of low-performing campaigns is a strong portfolio health signal. Lead Gen (197.0% ROI) is the weakest and the only campaign below 200% — it warrants a targeting review ahead of Q4.


### 4. Q4 Revenue Projection

| Scenario | Estimated Q4 Revenue | Basis |
|---|---|---|
| Baseline | ~$2,422,000 | Q3 average monthly revenue held flat |
| Conservative | ~$2,622,000 | 4% MoM growth (half of August's observed rate) |
| **Optimistic ★** | **~$2,824,000** | 8.4% MoM growth sustained — requires Holiday Promo activation + TikTok budget increase |

> **Projection Caveat:** These estimates are built on three months of Q3 data. As standard professional practice, short-term trend projections carry inherent uncertainty and should be treated as directional planning figures, not financial commitments.


### 5. Competitor Comparison Matrix
Benchmarked Savvy Daalytics Solutions against two simulated competitors — Digital Edge Pro (stronger by revenue) and MediaPulse Agency (weaker) — across financial performance, campaign efficiency, channel mix, and strategic positioning.

| Metric | Digital Edge Pro | **Savvy Daalytics Solutions** | MediaPulse Agency |
|---|---|---|---|
| Q3 Revenue | $2,780,000 | $2,422,385 | $1,680,000 |
| Overall ROI | 199.0% | **239.5% ★** | 171.8% |
| Revenue per $ Spent | $2.99 | **$3.40 ★** | $2.72 |
| Cost per Conversion | $8.54 | **$5.97 ★** | $7.63 |
| Channels Active | 6 | 5 | 4 |
| BI Reporting | Partial | **Full Power BI ★** | Manual |
| **Overall Rank** | #1 by Revenue | **#1 by ROI & Efficiency** | #3 |

**Takeaway:** Savvy Daalytics Solutions ranks second by raw revenue but first on every efficiency metric. The primary gap to close with Digital Edge Pro is budget scale and channel breadth — not performance quality.

> Competitor figures are derived from publicly available industry benchmarks and simulated estimates aligned to agencies of comparable size in the Canadian digital marketing sector. All figures should be interpreted directionally.


## Strategic Recommendations

1. **Scale TikTok Ads** — highest ROI channel at 259.6%; a 15–20% budget increase is the highest-ROI action available
2. **Activate Holiday Promo early in Q4** — top revenue campaign at $597,028 and 254.3% ROI
3. **Shift from CPC to CRO** — clicks-to-conversions correlation is weak; landing page quality is the real lever
4. **Review Lead Gen targeting** — only campaign below 200% ROI; audience segmentation refresh needed
5. **Set Q4 primary target at $2.65M**, with $2.82M as the stretch goal


## Tools & Methods Used

| Tool / Method | Application |
|---|---|
| Power BI Desktop | Trend line charts, scatter plots, segmentation visuals (Dashboard Pages 2–4) |
| DAX — SWITCH(TRUE()) | Performance segment calculated column with 300%/150% ROI thresholds |
| Microsoft Excel | Monthly aggregation cross-check and manual correlation review |
| Trend Projection | MoM growth rate extrapolation — conservative and optimistic scenarios |
| Benchmarking | Simulated competitor data aligned to Canadian digital marketing industry norms |