# HR-Employee-Performance-Attrition-Dashboard
An end-to-end HR analytics project using MySQL for data cleaning/analysis and Power BI for visual reporting and a business report 
# 📊 Employee Performance & Attrition Dashboard

## 📁 Project Overview
This repository features an end-to-end HR Analytics solution designed to track workforce composition, monitor tenure metrics, and uncover departmental turnover risks. By bridging robust **MySQL** database transformations with a highly polished **Power BI** executive dashboard, this project delivers actionable data storytelling to optimize human resource decision-making.

---

## 🧭 Executive Workflow

### 1️⃣ Advanced Data Engineering in MySQL
Raw workforce data underwent a rigorous extract, transform, and load (ETL) pipeline within MySQL. The SQL logic (`data_cleaning.sql` and `data_analysis.sql`) handles:
*   **Data Quality Assurance:** Standardizing date formats, resolving null entries, and handling missing values.
*   **Feature Engineering:** Generating business-critical dimensions including dynamic age brackets, calculating employee tenure, and structuring historical turnover markers.
*   **Metric Optimization:** Running complex analytical queries to pre-calculate high-level workforce metrics, shifting heavy processing loads from the reporting layer to the database level.

### 2️⃣ Optimized Pipeline Architecture
*   Structured SQL result sets were extracted as optimized datasets.
*   Pre-aggregating the data at the database level ensures the Power BI semantic model remains highly performant, lightweight, and scalable.

### 3️⃣ Premium Power BI Business Intelligence
The final dashboard was built away from standard Power BI defaults, focusing on modern corporate design patterns, scannability, and high executive utility.

#### 📌 Core Analytical Focus Areas:
*   **Workforce Profiling:** Executive tenure tracking, geographic distribution, and comprehensive organizational demographic splits.
*   **Retention & Risk Analysis:** Deep-dives into departmental attrition rates sorted by turnover severity to guide HR interventions.
*   **Granular Deep Dives:** Multi-dimensional cross-filtering covering departmental gender balance and age bracket dynamics.

---

## 📂 Repository Architecture
```text
HR-Employee-Performance-Dashboard/
│
├── 📁 1-SQL-Scripts/
│   ├── datacleaning.sql       # Enterprise data cleaning & standardization scripts
│   └── dataanalysis.sql       # Metric generation, business logic, & insights queries
│
├── 📁 2-PowerBI-Dashboard/
│   ├── Employee Performance Attrition Dashboard.pbix  # Polished Power BI file
│   └── HR Employee Report.jpeg
│
└── 📁 3-Datasets/
    ├── Resources.csv    # Source raw dataset
    

