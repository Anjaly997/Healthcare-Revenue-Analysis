
## Project Overview
End-to-end revenue cycle analytics dashboard analyzing $360M gross revenue 
and $214M net revenue across 24 months for a multi-payer healthcare organization.
Built entirely using SQL (SSMS) and Power BI.

## Business Problem
The organization had an 11.82% claim denial rate — significantly above the 8% 
MGMA industry benchmark — resulting in $145.79M in annual revenue leakage (40.52% 
of gross revenue).

## Key Findings
- **Root Cause:** Systemic process failure — all insurance × visit type combinations 
  showed identical 59.4–59.6% collection rates, ruling out payer mix or service mix 
  as drivers. Internal processes are failing uniformly.
- **Denial Trend:** Worsening — from 11.62% (Q1 2023) to 11.99% (Q4 2024)
- **Highest Risk:** Private outpatient (11.97%), Uninsured outpatient (12.48%)
- **Patient Segmentation:** 84% of patients drive 94% of revenue; high-risk segment 
  carries 12.10% denial rate

## Financial Impact Modeled
| Initiative | Annual Benefit | Investment | ROI |
|---|---|---|---|
| Appeals Program | $6.1M | $275K | 2,118% |
| Authorization Tracking | $7.1M | $180K | 3,844% |
| Care Coordination | $296K | $120K | 147% |
| **Total Year 1** | **$13.5M** | **$575K** | **2,248%** |

## Dashboard Pages
1. Revenue Overview — Gross/Net revenue, MoM trends, insurance breakdown
2. Denials & Utilization Analysis — Denial rates by payer, visit type, quarterly trend
3. Root Cause Analysis — Collection rate analysis, regional performance, leakage table
4. Financial Detail — Patient segmentation, utilization analysis, recovery modeling
5. Recommendations — 3 prioritized action plans with ROI and implementation roadmap
6. Executive Summary — Combined impact, sequencing, decisions required

## Tools Used
- **SQL (SSMS):** CTEs, window functions, aggregations, YoY trend analysis
- **Power BI:** DAX measures, Power Query, drill-through, conditional formatting
- **Excel:** Data preparation and validation

## SQL Highlights
- Denial rate calculation by payer × visit type combinations
- MoM and QoQ revenue trend analysis
- Patient segmentation by utilization tier
- Revenue leakage quantification at insurance level
