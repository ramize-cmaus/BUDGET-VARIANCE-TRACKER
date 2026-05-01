# Budget vs Actual Variance Tracker
### NovaTech Solutions Pvt. Ltd. | FY 2024–25 | IT Services

![Dashboard](01_dashboard_full.png)

---

## What this project does

A fully dynamic Excel workbook that tracks monthly budget vs actual
expenditure across 6 departments for a complete financial year (April
2024 – March 2025). Built to demonstrate management accounting, variance
analysis, and advanced Excel skills directly relevant to Financial
Analyst and FP&A intern roles.

---

## Screenshots

### Executive Dashboard
![Dashboard](01_dashboard_full.png)

### KPI Summary Cards
![KPI Cards](02_kpi_cards.png)

### Variance Analysis with Traffic-Light Formatting
![Variance Analysis](03_variance_analysis.png)

### Data Entry with Dropdown Validation
![Data Entry](04_data_entry.png)

---

## Workbook structure — 6 sheets

| Sheet | Purpose |
|-------|---------|
| Cover | Project details, disclaimer, usage instructions |
| Assumptions | Single source of truth for all 12 monthly budgets |
| Data Entry | 72 rows of actual monthly spend with dropdown validation |
| Calculations | SUMIFS engine — automated variance analysis for all departments |
| Dashboard | KPI cards, charts, status table, key insights |
| Raw Data | Source data reference |

---

## Key Excel features built

- **SUMIFS formula** — pulls actual spend by department AND month
  simultaneously from a named Excel Table (ActualData)
- **Dynamic formula references** — $A4 and C$3 mixed references allow
  one formula to copy across 72 cells correctly
- **Named Excel Table** (ActualData) — auto-expands when new data added
- **4-level traffic light system** — OVER BUDGET / WATCH / ON TRACK /
  UNDER BUDGET with conditional formatting
- **Data Validation dropdowns** — prevents spelling errors in department
  and month entries that would break SUMIFS
- **Protected formula cells** — only blue input cells are editable
- **Interactive dashboard** — KPI cards, bar chart, line trend chart,
  status summary table
- **Key Insights analyst commentary** — explains the WHY behind variances

---

## Company background — NovaTech Solutions

NovaTech Solutions Pvt. Ltd. is a fictional mid-size IT services company
based in Bengaluru, India. FY 2024–25 was a growth year — two UAE
enterprise contracts were won in Q1, a platform migration was completed
in Q2-Q3, and a campus recruitment drive ran in Aug–Nov.

All financial data is fictional and created to make the variance analysis
realistic and meaningful. Each variance has a documented business reason
in the Data Entry notes column and Key Insights dashboard section.

---

## Key findings from the analysis

- **Human Resources** — highest variance at +10.4% above budget,
  driven by mid-year campus recruitment drive (agency fees, assessments,
  induction events)
- **Technology & IT** — +6.9% over budget due to platform migration
  dual-infrastructure costs in Aug–Sep. Normalised post-migration.
- **Finance & Admin** — most controlled department at only +1.8% over
  budget throughout the full year
- **Overall company** — approximately 5% above budget, explained by
  deliberate growth investment decisions

---

## Design decisions I made

I chose to use a **named Excel Table** (ActualData) instead of a plain
cell range so the SUMIFS formulas auto-expand when new data rows are
added — critical for a live monthly tracker used throughout the year.

I separated Budget inputs (Assumptions sheet) from Actual inputs (Data
Entry sheet) to enforce clean model architecture — changing one budget
figure in Assumptions updates every formula in the workbook instantly.

I used **mixed cell references** ($A4 and C$3) in the SUMIFS formula so
one formula could be copied across all 72 cells without manual
adjustment — a key financial modelling discipline.

---

## Skills demonstrated

`Advanced Excel` `SUMIFS` `Named Tables` `Data Validation` `Conditional
Formatting` `Mixed Cell References` `Chart Design` `Management Accounting`
`Variance Analysis` `FP&A Reporting` `Budget vs Actual` `Financial
Modelling Principles` `Dashboard Design`

---

## Data disclaimer

All financial data in this workbook is entirely fictional and created
solely to demonstrate technical and analytical skills. NovaTech Solutions
Pvt. Ltd. is a fictional company. This workbook does not represent any
real company, organisation, or financial event.

---

## About me

**MUHAMMED RAMEES **
CMA (USA) Qualified | BCom Graduate
Advanced Excel with AI Integration | Power BI (in progress)
Skill-up: Tally | QuickBooks | Microsoft Dynamics 365 | UAE VAT & Corporate Tax | GST

Open to Financial Analyst, FP&A, and Management Accounting internship roles.

**LinkedIn:** https://www.linkedin.com/in/muhammed-ramees-b087bb259?utm_source=share_via&utm_content=profile&utm_medium=member_android**
**Email:**rameez.cmaus@gmail.com
