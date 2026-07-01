# Sql-Data-analysis-portfoli
# Business Performance & Activity Tracker Dashboard

An end-to-end Power BI solution designed to transform raw operational data into actionable business intelligence. This project features advanced data modeling, custom DAX measures, and interactive visualizations tailored for strategic decision-making.

🔗 **[Live Interactive Report Link / Portfolio Link]**  
*Note: If published via Power BI Service, insert your "Publish to Web" link here.*

---

## 🖼️ Dashboard Preview & Interface

*Replace these placeholders with actual screenshots or GIFs of your Tracker.pbix tabs to make the repo visually engaging.*

### 1. Executive Summary Tab
![Executive Summary Dashboard](<img width="1315" height="739" alt="image" src="https://github.com/user-attachments/assets/f701da2e-9f41-4654-bc37-33ad5f86b798" />
<img width="1900" height="734" alt="image" src="https://github.com/user-attachments/assets/ae323392-d82e-4e87-8d06-74d61439628a" />
)
*Provides a high-level overview of core KPIs, overall performance trends, and critical business health metrics.*

### 2. Operational Breakdown Tab
![Operational Insights](<img width="1914" height="815" alt="image" src="https://github.com/user-attachments/assets/bcb249f9-648c-4e02-ba49-ffd2b70f2841" />
)
*Allows deep-diving into specific categories, timelines, and regional/departmental performance.*

---

## 📊 Project Overview

### The Business Problem
Decision-makers often struggle to track performance metrics due to fragmented data scattered across disconnected operational logs. This dashboard resolves that bottleneck by consolidating historical activity into a unified, automated reporting system. 

The **Tracker.pbix** report provides business leaders with real-time visibility into operational efficiency, trends over time, and variance against targets, shifting the organization from reactive firefighting to proactive, data-driven planning.

---

## 🛠️ Data Source & Modeling

### 1. Data Extraction & ETL (Power Query)
* Raw data was extracted from `[<img width="1297" height="970" alt="image" src="https://github.com/user-attachments/assets/15d5516b-91c7-4ec0-801e-faf3fcca8670" />

]`.
* **Power Query (M)** was utilized for heavy data cleansing and transformation, which included:
  * Removing duplicates, handling null values, and enforcing strict data type formatting.
  * Unpivoting messy operational tables to create a clean, normalized structure.
  * Creating a dedicated, continuous **Calendar/Date Table** to support advanced Time Intelligence calculations.

### 2. Data Modeling & Architecture
The report utilizes a highly optimized **Star Schema** to ensure fast DAX calculation speeds and intuitive filtering behavior.
