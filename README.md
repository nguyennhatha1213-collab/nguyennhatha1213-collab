# Hi, I'm Ha 👋

## 📊 Aspiring Data Analyst | Customer Service & Operations Background

Welcome to my GitHub!

I have over **6 years of experience in Customer Service and Operations**, where I developed strong skills in communication, problem-solving, process improvement, and stakeholder management.

My passion for working with data inspired me to transition into **Data Analytics**. I enjoy transforming raw data into meaningful insights through dashboards, reports, and data-driven decision-making.

Currently, I am building my technical skills through hands-on projects using **SQL, Power BI, Excel, Power Query, Python, Supabase, and statistical analysis.**

---

# 🚀 Technical Skills

## 📈 Data Analytics

- **ETL Concepts:** Understand the Extract, Transform, and Load (ETL) process to collect, clean, transform, and prepare data from multiple sources for analysis and reporting.
- **SQL:** Extract, manipulate, and analyze data from relational databases for reporting and business analysis.
- **Power BI:** Power Query, data cleaning, data transformation, KPI reporting, DAX, data visualization, and dashboard design.
- **Excel / Google Sheets:** Data cleaning, transformation, analysis, Pivot Tables, visualization, and reporting.
- **Statistics & Analytics:** Descriptive statistics, data variability, distributions, anomaly detection, and relationships between variables.
- **Automation & Pipelines:** Building automated data ingestion pipelines using Python & cloud databases (Supabase).

---

# 💻 Tools

- Microsoft Excel / Google Sheets
- SQL Server
- Power BI Desktop
- Python
- Supabase
- GitHub
- Visual Studio Code

---

# 🏆 Certifications

- **Dua Data – Data Analyst Certificate** — August 3, 2026
- **SQLBolt Certificate** — August 5, 2026

---

# 📊 Featured Projects

## 📈 Technician Performance Dashboard

### 🔗 Project Link

**Repository:**  
[Technician Performance & Business Development](https://github.com/nguyennhatha1213-collab/nguyennhatha1213-collab/tree/main/Projects/Technician%20Performance%20%26%20Bussiness%20Development/Presentation.md)

---

## 📌 Project Overview

Built an interactive dashboard to evaluate technician performance through productivity, revenue, service quality, and operational efficiency metrics.

The dashboard supports management in:

- Monitoring operational KPIs
- Comparing regional performance
- Identifying operational bottlenecks
- Supporting data-driven decision-making

**Reporting Period:** Jan 2026 – Jun 2026

**Regions:** Central • North • South

---

### 🔄 Data Pipeline & System Architecture

| What | Mechanism | Frequency | Logic |
| :--- | :--- | :--- | :--- |
| **Operational & Job Data** | Extract from Enterprise ERP system (Work Orders, Repair Times, Technical Specs) | Daily Automated Batch Extract | Extract completed jobs (`Status = Completed`) and log durations for repair efficiency. |
| **Customer Feedback & CSAT** | Ingest from CRM System (Ratings, Complaints, Feedback Tickets) | Real-time / Scheduled API Sync | Join CRM tickets with ERP Work Order IDs to match customer ratings directly with specific technicians. |
| **Regional Performance & Targets** | Ingest manual operational Excel files (KPI Benchmarks, Technician Roster, Regional Targets) | Weekly / Monthly Manual Upload | Clean & standardize region codes, merge target KPIs with actual ERP/CRM performance metrics. |
| **Automated ETL Pipeline** | Python scripts & Supabase Cloud Storage | Scheduled Cron Job | Extract raw data from ERP, CRM, and Excel, perform automated data cleaning/transformations, and load into Supabase. |
| **Dashboard Transformation & Modeling** | Power Query & DAX Data Model | On-Demand / Scheduled Refresh | Calculate aggregated KPIs (MTTR, Complaint Rate, Revenue/Job) and generate interactive visuals. |

---

## 🛠 Tools Used

- Google Sheets
- Pivot Tables
- Dashboard Design
- KPI Reporting
- Data Visualization

---

## 📈 KPIs Tracked

| KPI | Value | Meaning |
|---|---:|---|
| Total Jobs | 54,263 | Total completed jobs |
| Total Revenue | 81,514 | Total revenue generated |
| Customer Rating | 4.58 | Average customer satisfaction |
| Average Repair Time | 44.86 min | Average repair duration |
| Complaint Rate | 1.32% | Percentage of customer complaints |
| Revenue per Job | 1.50 | Average revenue generated per job |

---

## 💼 Business Value

This dashboard supports data-driven decision-making through four key business perspectives.

### 1️⃣ Operational Performance Monitoring

- Consolidates **54,263 completed jobs** and **81,514 revenue units** over six months.
- Provides a centralized view of operational KPIs.
- Reduces manual reporting and improves monitoring efficiency.

---

### 2️⃣ Regional Performance Analysis

The **Central** region handled the highest workload (**19,513 jobs**) but did not achieve the highest customer satisfaction.

This may indicate:

- Technician workload imbalance
- Potential service quality risks
- The need to monitor **Jobs per Technician** rather than total jobs alone

---

### 3️⃣ Balancing Productivity and Service Quality

Although monthly workload fluctuated:

- Complaint Rate remained around **1.3%**
- Customer Rating stayed between **4.55–4.63**

This suggests that service quality remained relatively stable despite operational changes and provides a benchmark for other regions.

---

### 4️⃣ Early Risk Detection

Monitoring **Complaint Rate** together with **Customer Rating** enables early detection of potential operational issues.

Revenue per Job also helps evaluate:

- Pricing effectiveness
- Upselling opportunities
- Revenue efficiency

---

## 📌 Key Insights

- Central generated the highest workload but may face technician workload pressure.
- South maintained the fastest repair time while sustaining high customer satisfaction.
- Complaint Rate remained below the 2% operational benchmark used in this analysis.
- Customer Rating stayed consistently high throughout the reporting period.
- Revenue per Job remained relatively stable across regions.

---

## 💡 Recommendations

- Monitor **Jobs per Technician** to balance workload.
- Continue tracking **Complaint Rate** and **Customer Rating** together as early warning indicators.
- Investigate opportunities to improve **Revenue per Job** through pricing optimization or value-added services.
- Apply best-performing regional practices across all service locations.

---

## 📷 Dashboard Preview

<p align="center">
  <img src="./Image/Technician%20Performance%20dashboard%20(2).png" width="900">
</p>

---

# 🗄️ SQL Practice Repository

## 📚 Topics Covered

### SQL Fundamentals & Aggregation
- SELECT, WHERE, ORDER BY, DISTINCT, INSERT, UPDATE, ALTER TABLE
- Aggregation Functions: COUNT, SUM, AVG, MIN, MAX
- Grouping & Filtering: GROUP BY, HAVING

### Joins & Logic Processing
- Multi-table Joins: INNER JOIN, LEFT JOIN, RIGHT JOIN
- Conditional Logic: CASE WHEN
- Date & Time Functions: DATEDIFF, DATEADD, GETDATE()

### Intermediate & Advanced SQL
- **Common Table Expressions (CTEs):** Single CTE, Multiple CTEs, CTEs for complex business logic
- **Window & Ranking Functions:** ROW_NUMBER(), RANK(), DENSE_RANK(), LAG(), LEAD()
- **Advanced Pattern:** Combining CTEs with Window Functions for time-series analysis (e.g., MTTR, MTBF calculations)

---

## 🔄 Currently Learning & Practicing

### Advanced SQL Applications
- Complex Query Optimization & Indexing
- Stored Procedures & User-Defined Functions (UDFs)
- Real-world Business Case Studies (Cohort Analysis, Maintenance Analytics, Churn Rate)
---

# 📚 Learning Journey

## ✅ Completed

### Excel & Data Analytics

- Excel for Data Analysis
- Google Sheets Analytics
- Power BI Fundamentals
- SQL Server Fundamentals
- Git & GitHub

---

### 📊 Statistics for Data Analysis

- Descriptive Statistics
- Measures of Central Tendency
  - Mean
  - Median
  - Mode
- Measures of Dispersion
  - Range
  - Variance
  - Standard Deviation
  - Coefficient of Variation (CV)
- Quartiles & Percentiles
- Interquartile Range (IQR)
- Z-score
- Outlier Detection

---

## 🔄 In Progress

### 📊 Statistics for Data Analysis

- Probability
- Probability Distributions
- Sampling & Sampling Distributions
- Confidence Intervals
- Hypothesis Testing
- Correlation Analysis
- Regression Analysis

---

### 🐍 Python for Data Analysis

- NumPy
- Pandas
- Matplotlib
- Automation & Repetitive Task Automation (Python Scripts)
- Cloud Database Integration (Supabase)

---

### 🌐 REST API

- API Fundamentals
- Data Retrieval
- JSON Data

---

### ⚙️ Data Engineering Fundamentals

- Engineering & Maintenance Domain Data Pipeline Architecture
- ETL / ELT
- Automated Data Ingestion
- Data Pipelines
- Data Warehousing
- Airflow
- Docker

---

# 🎯 Career Goal

My goal is to become a professional **Data Analyst** who combines business knowledge with technical expertise to transform data into actionable insights.

I am passionate about continuous learning, solving business problems, and building dashboards that support better business decisions.

---

# 📂 Portfolio Repository

Explore more of my hands-on projects:

## 📁 Data-Analyst-Learning

- Automated Maintenance Data Pipeline (Python & Supabase)
- SQL Projects
- Power BI Dashboards
- Excel Analytics
- Statistics Exercises
- Python Projects *(Coming Soon)*

👉 [Explore my Data Analyst Learning Repository](https://github.com/nguyennhatha1213-collab/Data-Analyst-Learning)