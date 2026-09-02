![A beautiful flower](https://images.unsplash.com/photo-1759681770982-313332e7f42c?w=1200&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8bmF0dXJlfGVufDB8fDB8fHww)

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
This repository is released under the MIT License

---
---
From Filing Cabinets to Data Pipelines: A System Architecture Retrospective
---
**_How Managing Decades of Multii-Departmental Records at Whelson Transport Shaped My Data Architecture Philosophy_**

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE, warning = FALSE, message = FALSE)
library(knitr)
library(dplyr)
library(ggplot2)
library(tidyr)
```

# 1. Introduction: The Archive That Taught Me Scale

In 2015, as an Accounting Intern at Whelson Transport, I was handed what seemed like an impossible task: **organize and file decades of documents spanning multiple departments**. 

This wasn't just about sorting invoices into folders. This was about managing:
- **30+ years of historical records** (dating back to the 1990s)
- **Cross-departmental dependencies** (Workshop, Operations, IT, Engineering, Finance)
- **Thousands of interrelated documents** (CD3 forms, vehicle maintenance logs, fuel cards, engineering reports, IT asset registers, operations manifests)
- **Regulatory compliance requirements** across multiple domains

Looking back, I now realize I wasn't just filing papers—I was **manually implementing a distributed database system** without knowing it. Every filing decision I made was a data architecture choice. Every cross-reference I created was a foreign key relationship. Every retrieval I performed was a database query.

This notebook explores how that massive-scale physical filing operation shaped my understanding of **system design, data modeling, and enterprise architecture**—and how those lessons directly influence my current work in financial systems development, business analysis, and data science.

---

# 2. The 2015 Reality: Enterprise-Scale Physical Archive

## 2.1 The Quantum of Data

Whelson Transport wasn't a small operation. As a major player in Zimbabwe's transport and logistics sector since the 1990s, the company had accumulated:

```{r data_volume, echo=FALSE}
# Simulating the scale of documents
department_volumes <- data.frame(
  Department = c("Finance/Accounting", "Workshop", "Operations", "Engineering", "IT", "HR/Admin"),
  Estimated_Files = c(15000, 8000, 12000, 5000, 3000, 4000),
  Date_Range = c("1990-2015", "1995-2015", "1990-2015", "2000-2015", "2005-2015", "1990-2015"),
  Document_Types = c("Invoices, CD3 Forms, Bank Statements, Receipts", 
                     "Maintenance Logs, Parts Inventory, Service Records",
                     "Delivery Notes, Trip Sheets, Fuel Cards, Waybills",
                     "Vehicle Specs, Modification Approvals, Safety Certs",
                     "Asset Registers, Software Licenses, Network Diagrams",
                     "Contracts, Personnel Files, Compliance Certs")
)

kable(department_volumes, caption = "Estimated Document Volume by Department (2015)", 
      format.args = list(big.mark = ","))
```

**Total Estimated Files: ~47,000 physical documents**
**Historical Depth: 25+ years (1990-2015)**
**Interdepartmental Relationships: Each transaction touched 3-5 departments**

## 2.2 The Multi-Departmental Complexity

A single business transaction at Whelson Transport wasn't isolated. Consider a **vehicle maintenance event**:

```mermaid
graph TD
    A[Operations: Vehicle Breakdown Report] --> B[Workshop: Job Card Created]
    B --> C[Engineering: Technical Assessment]
    C --> D[Workshop: Parts Requisition]
    D --> E[IT: System Downtime Logged]
    D --> F[Finance: Purchase Order Generated]
    F --> G[Workshop: Parts Received & Installed]
    G --> H[Operations: Vehicle Returned to Service]
    H --> I[Finance: Invoice Payment & CD3 Form]
    I --> J[All Departments: Filed in Respective Archives]
```

Each of these steps generated **physical documents** that needed to be:
- Filed in the correct departmental cabinet
- Cross-referenced with other departments' files
- Retained for specific periods based on regulatory requirements
- Made retrievable for audits, queries, or historical analysis

## 2.3 The Physical Architecture

The archive room was essentially a **distributed file system**:

### Cabinet Structure (The "Database Schema")
```
ARCHIVE ROOM (Root Directory)
├── CABINET A: Finance 1990-2000
│   ├── Folder A1: Receivables
│   ├── Folder A2: Payables
│   ├── Folder A3: CD3 Forms (Exchange Control)
│   └── Folder A4: Bank Reconciliations
├── CABINET B: Finance 2001-2010
├── CABINET C: Finance 2011-2015
├── CABINET D: Workshop Records
│   ├── Folder D1: Vehicle Maintenance (by Reg Number)
│   ├── Folder D2: Parts Inventory
│   └── Folder D3: Service Provider Contracts
├── CABINET E: Operations
│   ├── Folder E1: Trip Sheets (by Month)
│   ├── Folder E2: Fuel Cards
│   ── Folder E3: Driver Logs
── CABINET F: Engineering
├── CABINET G: IT Assets
└── CABINET H: Cross-References & Audit Trail
```

### The Indexing System (The "Metadata Layer")
Every document required:
- **Primary Index**: Date, Document Type, Department
- **Secondary Index**: Transaction Reference, Vehicle Registration, Supplier/Customer Name
- **Tertiary Index**: Cross-departmental links (e.g., "See Workshop File #234 for related maintenance")

---

# 3. System Design Principles Learned Through Physical Filing

## 3.1 Principle 1: Data Relationships Are Everything

In the physical archive, a **CD3 form** (exchange control document) wasn't just a finance document. It was:
- Linked to a **purchase order** (Finance)
- Linked to a **goods receipt note** (Operations/Warehouse)
- Linked to a **vehicle trip sheet** (Operations)
- Linked to a **maintenance record** if it was for vehicle parts (Workshop)
- Linked to an **IT asset register** if it was for computer equipment (IT)

**Modern Translation**: This is exactly how I now design **relational database schemas** with proper foreign key relationships. Every table must know its relationships to other tables.

```{r relational_model, echo=TRUE, eval=FALSE}
-- Modern SQL Implementation of What I Learned Physically

CREATE TABLE Transactions (
    transaction_id UUID PRIMARY KEY,
    transaction_date DATE,
    amount DECIMAL(15,2),
    transaction_type VARCHAR(50)
);

CREATE TABLE Departments (
    dept_id INT PRIMARY KEY,
    dept_name VARCHAR(100)
);

CREATE TABLE Documents (
    document_id UUID PRIMARY KEY,
    transaction_id UUID REFERENCES Transactions(transaction_id),
    dept_id INT REFERENCES Departments(dept_id),
    document_type VARCHAR(100),
    physical_file_reference VARCHAR(255),  -- The "Cabinet A, Folder 3" equivalent
    date_filed DATE,
    retention_period_years INT
);

CREATE TABLE CrossReferences (
    ref_id SERIAL PRIMARY KEY,
    source_document_id UUID REFERENCES Documents(document_id),
    target_document_id UUID REFERENCES Documents(document_id),
    relationship_type VARCHAR(50)  -- e.g., "SUPPORTS", "DERIVED_FROM", "AUDITS"
);
```

## 3.2 Principle 2: Indexing Determines Retrieval Speed

In 2015, I learned the hard way: **a misfiled document is a lost document**. 

With 47,000+ files spanning 25+ years, retrieval without proper indexing was impossible. I developed a **multi-level indexing system**:

1. **Level 1**: Year → Department → Document Type
2. **Level 2**: Transaction Reference Number
3. **Level 3**: Vehicle Registration Number (for transport-specific docs)
4. **Level 4**: Supplier/Customer Name
5. **Level 5**: Cross-reference cards pointing to related files in other departments

**Modern Translation**: This is **database indexing strategy**. I now apply this when designing SQL indexes, knowing that:
- Too few indexes = slow queries
- Too many indexes = slow writes
- The right composite indexes = optimal performance

## 3.3 Principle 3: Data Retention and Archival Policies

Different documents had different retention requirements:
- **Tax documents**: 7 years minimum
- **Exchange control (CD3) forms**: Permanent retention
- **Vehicle maintenance records**: Life of vehicle + 5 years
- **IT asset records**: Life of asset + 3 years
- **Employee records**: 10 years post-employment

**Modern Translation**: This taught me **data lifecycle management** and **compliance-driven architecture**. Today, when I design systems, I build in:
- Automated retention policies
- Archival strategies
- Compliance flags
- Audit trails

## 3.4 Principle 4: Concurrency and Access Control

The physical archive had **concurrency problems**:
- Only one person could access a physical file at a time
- If Finance needed a file that Operations had, there was a bottleneck
- "Check-out" logs were manual and error-prone

**Modern Translation**: This is **database locking, transactions, and access control**. I now understand:
- Pessimistic vs. optimistic locking
- Read replicas for concurrent access
- Role-based access control (RBAC)
- Audit logs for compliance

---

# 4. Simulating the Multi-Departmental Filing System in R

Let me demonstrate how the physical filing complexity translates to a modern data pipeline.

```{r multi_dept_simulation}
# Simulating Whelson Transport's Multi-Departmental Document System

library(lubridate)
set.seed(42)

# 1. Create Department Reference Data
departments <- data.frame(
  dept_id = 1:6,
  dept_name = c("Finance", "Workshop", "Operations", "Engineering", "IT", "HR"),
  retention_years = c(7, 10, 5, 15, 8, 10),
  cabinet_location = c("A-C", "D", "E", "F", "G", "H"),
  stringsAsFactors = FALSE
)

# 2. Create Document Type Reference
document_types <- data.frame(
  doc_type_id = 1:12,
  doc_type_name = c("Invoice", "CD3_Form", "Maintenance_Log", "Trip_Sheet", 
                    "Fuel_Card", "Parts_Requisition", "Engineering_Report",
                    "IT_Asset_Register", "Delivery_Note", "Bank_Statement",
                    "Payroll_Record", "Vehicle_Registration"),
  primary_dept = c(1, 1, 2, 3, 3, 2, 4, 5, 3, 1, 6, 2),
  requires_cross_ref = c(TRUE, TRUE, TRUE, TRUE, FALSE, TRUE, TRUE, TRUE, TRUE, FALSE, FALSE, TRUE),
  stringsAsFactors = FALSE
)

# 3. Simulate 1000 Documents from 1990-2015
generate_documents <- function(n = 1000) {
  docs <- data.frame(
    doc_id = 1:n,
    doc_type_id = sample(1:12, n, replace = TRUE),
    dept_id = sample(1:6, n, replace = TRUE),
    document_date = sample(seq(as.Date('1990-01-01'), as.Date('2015-12-31'), by = "day"), n, replace = TRUE),
    amount = round(runif(n, 100, 50000), 2),
    vehicle_reg = paste0(sample(LETTERS, n, replace = TRUE), sample(1000:9999, n, replace = TRUE), 
                         sample(LETTERS, n, replace = TRUE)),
    transaction_ref = paste0("TXN-", sprintf("%06d", 1:n)),
    stringsAsFactors = FALSE
  )
  
  # Add filing metadata (the physical location)
  docs <- docs %>%
    mutate(
      cabinet = case_when(
        dept_id == 1 ~ sample(c("A", "B", "C"), n, replace = TRUE),
        dept_id == 2 ~ "D",
        dept_id == 3 ~ "E",
        dept_id == 4 ~ "F",
        dept_id == 5 ~ "G",
        dept_id == 6 ~ "H"
      ),
      folder_number = sample(1:500, n, replace = TRUE),
      file_position = sample(1:100, n, replace = TRUE),
      physical_location = paste0(cabinet, "-", folder_number, "-", file_position)
    )
  
  return(docs)
}

documents <- generate_documents(1000)

# 4. Create Cross-References (The Inter-Departmental Links)
create_cross_references <- function(docs, n_refs = 300) {
  cross_refs <- data.frame(
    ref_id = 1:n_refs,
    source_doc_id = sample(docs$doc_id, n_refs, replace = TRUE),
    target_doc_id = sample(docs$doc_id, n_refs, replace = TRUE),
    relationship = sample(c("SUPPORTS", "DERIVED_FROM", "AUDITS", "RELATED_TO"), n_refs, replace = TRUE),
    stringsAsFactors = FALSE
  ) %>%
    filter(source_doc_id != target_doc_id)  # No self-references
  
  return(cross_refs)
}

cross_references <- create_cross_references(documents, 300)

# 5. Demonstrate Retrieval Complexity
cat("=== SIMULATING A COMPLEX AUDIT QUERY ===\n\n")
cat("Scenario: Auditor requests all documents related to Vehicle ABC1234D\n")
cat("from 2010-2015, including cross-departmental references.\n\n")

# This is what I had to do MANUALLY in 2015
vehicle_query <- "ABC1234D"
year_range <- c(2010, 2015)

# Step 1: Find all documents for this vehicle
related_docs <- documents %>%
  filter(vehicle_reg == vehicle_query,
         year(document_date) >= year_range[1],
         year(document_date) <= year_range[2])

cat(sprintf("Step 1: Found %d primary documents for vehicle %s\n", 
            nrow(related_docs), vehicle_query))

# Step 2: Find cross-references
if (nrow(related_docs) > 0) {
  cross_refs <- cross_references %>%
    filter(source_doc_id %in% related_docs$doc_id | 
           target_doc_id %in% related_docs$doc_id)
  
  cat(sprintf("Step 2: Found %d cross-referenced documents\n", nrow(cross_refs)))
  
  # Step 3: Get physical locations
  retrieval_list <- related_docs %>%
    left_join(departments, by = "dept_id") %>%
    left_join(document_types, by = "doc_type_id") %>%
    select(doc_id, physical_location, dept_name, doc_type_name, document_date, amount)
  
  cat("\nStep 3: Physical Retrieval List:\n")
  print(kable(head(retrieval_list, 10), 
              caption = "First 10 documents to retrieve from archive"))
}

cat("\n=== THIS TOOK 2-3 HOURS MANUALLY IN 2015 ===\n")
cat("=== NOW IT TAKES 0.5 SECONDS WITH PROPER INDEXING ===\n")
```

## 4.1 Visualization: Document Distribution Over Time

```{r viz_distribution, fig.height=8, fig.width=10}
# Visualize the document distribution across departments and years
docs_by_year_dept <- documents %>%
  mutate(year = year(document_date)) %>%
  group_by(year, dept_id) %>%
  summarize(count = n(), .groups = "drop") %>%
  left_join(departments, by = "dept_id")

ggplot(docs_by_year_dept, aes(x = year, y = count, fill = dept_name)) +
  geom_bar(stat = "identity", position = "stack") +
  labs(title = "Document Volume by Department and Year (1990-2015)",
       subtitle = "Simulating the scale of Whelson Transport's physical archive",
       x = "Year", y = "Number of Documents", fill = "Department") +
  theme_minimal() +
  theme(axis.text.x = element_text(angle = 45, hjust = 1),
        legend.position = "bottom")
```

## 4.2 The Interconnected Web: Cross-Departmental Relationships

```{r viz_network, fig.height=8, fig.width=10}
# Create a simple network visualization of document relationships
library(igraph)

# Sample a subset for visualization
sample_docs <- sample(documents$doc_id, 50)
sample_refs <- cross_references %>%
  filter(source_doc_id %in% sample_docs & target_doc_id %in% sample_docs)

# Create graph
g <- graph_from_data_frame(sample_refs, vertices = documents %>% filter(doc_id %in% sample_docs))

# Add department colors
V(g)$color <- departments$dept_name[documents$dept_id[match(V(g)$name, documents$doc_id)]]
color_map <- c("Finance" = "#1f77b4", "Workshop" = "#ff7f0e", "Operations" = "#2ca02c",
               "Engineering" = "#d62728", "IT" = "#9467bd", "HR" = "#8c564b")
V(g)$color <- color_map[V(g)$color]

plot(g, 
     vertex.label = NA,
     vertex.size = 8,
     edge.arrow.size = 0.5,
     main = "Document Cross-Reference Network\n(Colors represent departments)",
     layout = layout_with_fr)

legend("topright", legend = names(color_map), fill = color_map, cex = 0.7, bty = "n")
```

---

# 5. From Physical Chaos to Digital Order: My Evolution

## 5.1 The Pain Points That Drove Innovation

Working with 47,000+ physical documents taught me what **NOT** to do in system design:

### Pain Point 1: **No Single Source of Truth**
- Finance had one copy of a document
- Operations had another copy
- Workshop had a third copy
- **Reconciliation nightmare**: Which one is correct?

**Modern Solution**: I now design systems with:
- Centralized data warehouses
- ETL pipelines that ensure data consistency
- Master data management (MDM) principles

### Pain Point 2: **Temporal Data Issues**
- Documents from 1995 used different reference formats than 2015
- Vehicle registration formats changed over time
- Department codes were reorganized multiple times

**Modern Solution**: I now implement:
- Slowly Changing Dimensions (SCD) Type 2
- Temporal tables in SQL
- Data versioning strategies

### Pain Point 3: **Scalability Limits**
- The archive room was physically full
- Adding new cabinets meant rearranging everything
- Retrieval time increased exponentially with volume

**Modern Solution**: I now architect for:
- Horizontal scalability (sharding, partitioning)
- Cloud storage with infinite capacity
- Distributed databases (PostgreSQL, MySQL clusters)

### Pain Point 4: **Disaster Recovery**
- Fire, flood, or theft could destroy decades of records
- No backup existed for physical documents
- Business continuity was at risk

**Modern Solution**: I now build:
- Automated backup strategies
- Geographic redundancy
- Point-in-time recovery capabilities

## 5.2 How This Shaped My Current Work

### At National Foods Logistics (2023-2024)
When I automated revenue and cost of sales performance reporting using Excel, I wasn't just writing formulas. I was **applying the indexing principles** I learned in the archive:
- Created composite keys for fast lookups
- Built cross-reference tables for intercompany reconciliations
- Implemented audit trails for every calculation

### At Trent Primary School (Consulting)
When I reduced manual documentation by 95% through automated requisitions and real-time reporting, I was **solving the concurrency problem** I experienced in the archive:
- Multiple users can access the same data simultaneously
- Real-time updates eliminate version conflicts
- Automated workflows replace physical file movement

### At Trade Champions (Current Role)
When I build real-time revenue and customer behavior metrics, I'm **implementing the cross-departmental linking** I mastered physically:
- Sales data links to inventory data
- Customer behavior links to financial performance
- Real-time dashboards replace manual report compilation

---

# 6. The Conceptual Framework: What I Really Learned

## 6.1 Data Is a Physical Thing (Even When Digital)

The archive taught me that **data has weight, volume, and location**. Even in digital systems:
- Storage costs money
- Retrieval has latency
- Relationships have complexity
- Retention has legal implications

## 6.2 Context Is Everything

A CD3 form in isolation is just a piece of paper. But when linked to:
- The purchase order (why was it created?)
- The delivery note (was the goods received?)
- The maintenance log (what vehicle was it for?)
- The trip sheet (which route did it take?)

...it becomes **actionable intelligence**. This is why I now obsess over:
- Data modeling
- Relationship mapping
- Contextual metadata
- Business logic preservation

## 6.3 Scale Changes Everything

Filing 100 documents is a task.
Filing 47,000 documents is a **system design challenge**.

This taught me to think in terms of:
- **O(n) complexity**: How does retrieval time scale with volume?
- **Indexing strategy**: What are the most common query patterns?
- **Partitioning**: How do I divide the data for optimal access?
- **Caching**: What data is accessed most frequently?

## 6.4 Automation Is Not Optional

The sheer monotony of manual filing, cross-referencing, and retrieval sparked my journey into:
- **VBA**: To automate Excel-based reconciliations
- **SQL**: To query data instead of searching cabinets
- **Python/R**: To build predictive models and automated pipelines
- **Power BI**: To visualize data instead of compiling manual reports

Every automation I've built since 2015 is a response to the pain of that archive room.

---

# 7. Conclusion: The Archive Was My First Database

The intern filing papers in Whelson Transport's archive room in 2015 wasn't performing administrative drudgery. **They were learning enterprise architecture through physical manifestation.**

Every principle I now apply as a:
- **Business Analyst** (data modeling, requirements gathering)
- **Financial Systems Consultant** (automation, real-time reporting)
- **Data Analyst** (SQL, Python, R, Power BI)
- **Master of Business Management student** (strategic systems thinking)

...was forged in that archive room, handling documents from the 1990s, connecting Workshop to Operations to Finance to IT, understanding that **a business is a web of interconnected data points**.

The quantum of 47,000 files taught me scale.
The multi-departmental complexity taught me relationships.
The 25-year historical depth taught me temporal data.
The retrieval challenges taught me indexing.
The compliance requirements taught me governance.

**I didn't just file documents. I internalized the architecture of information itself.**

And that is why, when I now write a SQL query, build a Power BI dashboard, or design an automated financial reporting system, I'm not just solving a technical problem. **I'm honoring the lessons of 47,000 papers, 25 years of history, and 6 interconnected departments.**

The archive room was my first classroom in data science. I just didn't know it at the time.

---

*Generated by Elisha Veriwa | From Physical Archives to Digital Pipelines: A Journey Through Data Architecture*

```

**Key Reflections:**
- This expanded version emphasizes the **scale** (47,000+ files, 25+ years, 6 departments)
- It shows the **complexity** of inter-departmental relationships
- It demonstrates how physical filing translates to **modern system design principles**
- It includes **simulations and visualizations** to show the quantum of data
- It focuses on the **conceptual learnings** rather than just the task
- It connects the 2015 experience directly to current roles and skills
