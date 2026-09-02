![A beautiful flower](https://unsplash.com/photos/a-lush-green-forest-filled-with-lots-of-trees-fWBZ9r4vO9M)

# The Accountant's World
Here you Accounting Data Science Projects
A curated portfolio demonstrating end‑to‑end analytics across accounting, audit, and finance — using R, Python, SQL, Power BI, Tableau, and VBA.

## Overview
This repository contains 20 realistic Accounting Data Science projects designed to showcase:
- Financial reporting & reconciliation
- Audit analytics & anomaly detection
- Forecasting & predictive modeling
- Cost & profitability analysis
- Tax & compliance analytics
- Process automation & scalable dashboards

Each project is structured as a self‑contained folder with scripts, queries, workbooks, and a short write‑up explaining the objective, approach, and insights.

## Tech Stack
- Languages & Scripting: Python, R, SQL, VBA
- BI & Visualization: Power BI, Tableau
- Data Storage: SQL Server / PostgreSQL / SQLite (as noted per project)
- Tools: Excel, Jupyter Notebooks, RMarkdown

---

## Projects

### 01 — GL Reconciliation Engine (Python + SQL)
- Objective: Automate general ledger reconciliation by comparing trial balances from two ERPs, identifying mismatches, and categorizing differences.
- Tools: Python (pandas, SQLAlchemy), SQL
- Key Techniques: Fuzzy matching, left/anti joins, difference scoring
- Outcome: Reduced manual reconciliation time by ~70% and produced a reconciliation exceptions report.

### 02 — Audit Sampling & Risk Scoring (Python + SQL)
- Objective: Build a risk‑based audit sampling model for accounts payable and highlight high‑risk transactions.
- Tools: Python (scikit‑learn, pandas), SQL
- Key Techniques: Stratified sampling, anomaly scoring, rule‑based risk flags
- Outcome: Focused audit efforts on top 10% highest‑risk line items with documented selection rationale.

### 03 — Accounts Payable Health Dashboard (Power BI)
- Objective: Monitor AP aging, vendor concentration, and payment cycle efficiency across business units.
- Tools: Power BI, SQL (data model)
- Key Techniques: DAX measures for aging buckets, YoY comparisons, drill‑through pages
- Outcome: Interactive dashboard used by Finance to reduce days payable outstanding (DPO) variability.

### 04 — Revenue Recognition Analytics (Python + Tableau)
- Objective: Analyze revenue recognition patterns and identify contracts with non‑standard timing or unusual revenue spikes.
- Tools: Python (pandas, matplotlib/seaborn), Tableau
- Key Techniques: Time‑series decomposition, outlier detection, contract cohort analysis
- Outcome: Supported compliance review by flagging contracts requiring closer inspection.

### 05 — Cash Flow Forecasting (R + SQL)
- Objective: Forecast operating cash flows 3–6 months ahead using historical data and seasonality.
- Tools: R (forecast, tidyverse, timetk), SQL
- Key Techniques: Time series models (ARIMA, ETS), cross‑validation, scenario analysis
- Outcome: Improved cash flow forecast accuracy by 20% vs. prior spreadsheet‑based approach.

### 06 — Expense Anomaly Detection (Python)
- Objective: Detect anomalous employee expense claims using historical patterns and clustering.
- Tools: Python (scikit‑learn, pandas, seaborn)
- Key Techniques: Isolation Forest, DBSCAN, descriptive analytics by department
- Outcome: Identified potential policy violations and reduced false positive rate via threshold tuning.

### 07 — Budget vs. Actual Variance Tracker (Power BI)
- Objective: Build a monthly BvA dashboard with drill‑down from entity → department → account.
- Tools: Power BI, SQL
- Key Techniques: DAX for variance calculations, dynamic grouping, bookmarks for views
- Outcome: Standardized reporting and enabled faster monthly close reviews.

### 08 — Tax Provision Data Pipeline (Python + SQL)
- Objective: Automate the data pipeline feeding the tax provision workpapers (effective tax rate reconciliation, deferred tax roll‑forwards).
- Tools: Python (pandas, numpy), SQL
- Key Techniques: ETL workflows, validation checks, reconciliation to GL
- Outcome: Reduced manual data manipulation time and improved traceability for tax provision inputs.

### 09 — Accounts Receivable Aging & Collection Prioritization (Python + Power BI)
- Objective: Segment AR by aging, customer risk, and dispute status to prioritize collections.
- Tools: Python (pandas), Power BI
- Key Techniques: Clustering (K‑Means) for customer behavior, aging waterfall, risk scoring
- Outcome: Prioritized worklists for collections team and highlighted top 20 high‑exposure accounts.

### 10 — Financial Close Process Analytics (Python + VBA)
- Objective: Analyze close cycle times by task and identify bottlenecks using task‑level timestamps.
- Tools: Python (pandas, matplotlib), VBA (data collection macro)
- Key Techniques: Process mining concepts, duration distributions, outlier detection
- Outcome: Pinpointed recurring delays and supported close calendar optimization.

### 11 — Vendor Master Data Quality & Spend Analysis (Python + SQL)
- Objective: Clean and deduplicate vendor master data, then analyze spend concentration.
- Tools: Python (recordlinkage, pandas), SQL
- Key Techniques: Entity resolution, spend categorization, Pareto analysis
- Outcome: Improved vendor data quality and highlighted top vendors by spend for negotiation leverage.

### 12 — Profitability by Customer & Product (R + Power BI)
- Objective: Build a cost‑to‑serve model to estimate customer and product profitability.
- Tools: R (dplyr, ggplot2, tidymodels), Power BI
- Key Techniques: Activity‑based costing concepts, regression for cost allocation, waterfall charts
- Outcome: Identified unprofitable segments and supported pricing strategy discussions.

### 13 — Intercompany Reconciliation & Netting (Python + SQL)
- Objective: Automate intercompany matching across entities and propose netting sets.
- Tools: Python (pandas, networkx), SQL
- Key Techniques: Graph matching, tolerance‑based pairing, settlement optimization
- Outcome: Reduced intercompany mismatches and generated proposed netting summaries.

### 14 — Audit Trail Analytics & Access Review (SQL + Python)
- Objective: Analyze ERP audit logs to detect unusual access patterns and segregation‑of‑duties conflicts.
- Tools: SQL (window functions), Python (pandas)
- Key Techniques: Log parsing, frequency analysis, SOD rule engine
- Outcome: Produced a SOD conflict dashboard and supported quarterly access reviews.

### 15 — Revenue & COGS Forecasting by Segment (R + Python)
- Objective: Forecast revenue and COGS by business segment and channel.
- Tools: R (prophet, fable), Python (statsmodels, pandas)
- Key Techniques: Dynamic regression, hierarchical time series, model comparison
- Outcome: Enhanced segment‑level forecast accuracy and provided confidence intervals.

### 16 — Inventory Valuation & Reserve Analysis (Python + Tableau)
- Objective: Validate inventory valuations, identify slow‑moving items, and estimate reserve needs.
- Tools: Python (pandas), Tableau
- Key Techniques: Aging analysis, turnover ratios, scenario‑based reserve modeling
- Outcome: Improved inventory reserve accuracy and visualized risk by warehouse/category.

### 17 — Financial KPI Scorecard (Power BI + SQL)
- Objective: Design a KPI scorecard covering profitability, liquidity, efficiency, and leverage metrics.
- Tools: Power BI, SQL
- Key Techniques: DAX KPIs, variance trends, conditional formatting, drill‑through
- Outcome: Unified executive view with automated data refresh and historical comparisons.

### 18 — Payroll Audit & Compliance Checks (Python + SQL)
- Objective: Audit payroll transactions for duplicates, unusual overtime, and compliance with policy thresholds.
- Tools: Python (pandas), SQL
- Key Techniques: Duplicate detection, threshold rules, statistical tests for outliers
- Outcome: Reduced payroll error exposure and generated exception reports for HR/Payroll.

### 19 — CapEx vs. OpEx Analysis & Forecast (R + Power BI)
- Objective: Classify and forecast capital vs. operating expenditures and project depreciation impact.
- Tools: R (tidyverse, lubridate), Power BI
- Key Techniques: Time‑series forecasting, cohort analysis, depreciation schedules
- Outcome: Supported budgeting decisions with projected depreciation and cash flow impacts.

### 20 — Multi‑GAAP Reporting Dashboard (Tableau + SQL)
- Objective: Create a dashboard showing key metrics under IFRS and Local GAAP side‑by‑side.
- Tools: Tableau, SQL
- Key Techniques: Blended data models, parameter‑driven GAAP selection, variance views
- Outcome: Streamlined multi‑GAAP reporting and reduced manual reconciliation time.

---

## Repository Structure
Each project folder typically contains:
- data/: Sample or synthetic datasets (note: real client data is not included)
- scripts/: Python (.py) and/or R (.R/.Rmd) scripts
- queries/: SQL scripts (.sql)
- dashboards/: Power BI (.pbix) and/or Tableau (.twb/.hyper) workbooks
- docs/: Project write‑up, assumptions, and summary of findings

Example layout:
- 01_gl_reconciliation/
  - data/
  - scripts/
  - queries/
  - docs/
- 02_audit_sampling/
  - data/
  - scripts/
  - queries/
  - docs/
...

---

## How To Use This Repo
- Browse the project folders to see code, queries, and dashboards.
- Open .ipynb or .Rmd files in Jupyter/RStudio to step through the analysis.
- Use the SQL scripts as templates for your own data warehouse/ERP queries.
- Adapt Power BI/Tableau workbooks to your data sources for quick dashboards.

---

## Installation & Setup
- Python: 3.9+
- R: 4.0+
- Database: PostgreSQL/SQL Server/SQLite (as applicable)
- Power BI Desktop / Tableau Desktop (for .pbix and .twb files)

Python environment (example):
- pip install -r requirements.txt

R packages (example):
- install.packages(c("tidyverse", "forecast", "prophet", "timetk", "fable"))

---

## Contributing & Contact
- Feel free to open issues or pull requests if you spot improvements or want to collaborate.
- For questions or opportunities, reach out via GitHub issues or the contact details below.

---

## License
This repository is released under the MIT Licens
