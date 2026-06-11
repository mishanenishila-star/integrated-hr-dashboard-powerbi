# integrated-hr-dashboard-powerbi
Integrated HR Dashboard for a Natural Foods Cluster – built in Power BI with a star schema data model in Excel. Covers workforce, attrition, performance &amp; financial KPIs for FY 2025/26.

**Tool:** Power BI Desktop  
**Data Model:** Star Schema (Excel)  
**Period:** FY 2025/2026 (Apr 2025 – Mar 2026)

## Overview
A multi-page HR analytics dashboard built for a natural foods manufacturing cluster 
with 3 companies (A, B, C) and ~422 employees. Covers workforce composition, 
attrition trends, performance KPIs, and financial-HR linkage.

## Dashboard Pages

| Page | Description |
|------|-------------|
| Home | Navigation landing page with attrition ticker |
| Executive Overview | KPI cards, headcount, revenue vs salary cost, Kgs/Head |
| Workforce & Talent | Gender/age/dept breakdown, attrition trend, resignations |
| Performance & Development | OT variance, PDP completion, absenteeism, promotions |
| Detailed Data | Drill-through table for financials & HR metrics |

## Key Metrics Tracked
- Headcount, YTD Resignations, Attrition Rate
- Employee Cost % of Revenue
- OT Variance %, Absenteeism Rate
- PDP Completion %, Internal Promotion %, Regrettable Loss %

## Data Model
Star schema designed in Excel with the following tables:
- **Fact tables:** Financials & Productivity, HR Metrics
- **Dimension tables:** Emp Master, Calendar, Cluster_Dim, KPIs

## Screenshots
![Home](screenshots/01_home.png)
![Executive Overview](screenshots/02_executive_overview.png)
![Workforce & Talent](screenshots/03_workforce_talent.png)
![Performance & Development](screenshots/04_performance_development.png)
![Detailed Data](screenshots/05_detailed_data.png)
