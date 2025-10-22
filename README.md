# 🧮 SQL Exploratory Data Analysis (EDA)

## 🧠 Background & Business Context
This project showcases a series of **SQL-based exploratory data analyses** performed on datasets sourced from a simulated business data warehouse.  
It reflects the typical workflow of a **Business Intelligence Analyst**, exploring raw data to uncover trends, segment performance, and generate actionable insights for reporting and strategy.

The project is built using **PostgreSQL** and demonstrates practical query design across multiple business domains — from sales and customer analytics to operational KPIs and cumulative reporting.

---

## 🎯 Objective
To perform structured SQL-based exploration and develop analytical scripts that help:
- Understand data structures and key metrics within a warehouse environment.  
- Uncover patterns in sales, customer behavior, and time-based performance.  
- Create reusable SQL snippets that accelerate analytical reporting and dashboard preparation.  
- Simulate the hands-on work of a BI professional exploring live data for insights.

---

## 💼 Business Value
This repository mirrors how data teams deliver value using SQL:
- **Faster Decision-Making:** Pre-built analytical queries reduce time to insight.  
- **Standardized EDA Approach:** Ensures consistent and repeatable exploration workflows.  
- **Scalable Insights:** Enables analysts to extend the queries for dashboard and KPI reporting.  
- **Cross-Domain Usability:** Each script can be adapted for multiple business contexts (sales, HR, finance, marketing, etc.).

---

## 🗂️ Project Structure

| Script | Description |
|--------|--------------|
| `00_init_database.sql` | Database setup, schema inspection, and connection validation. |
| `01_database_exploration.sql` | Overview of tables, schemas, record counts, and metadata. |
| `02_dimensions_exploration.sql` | Exploration of key business dimensions (customers, products, regions). |
| `03_date_range_exploration.sql` | Identification of time windows and data completeness checks. |
| `04_measures_exploration.sql` | Computation of key business measures — revenue, profit, sales quantity. |
| `05_magnitude_analysis.sql` | Ranking and scaling metrics by category, region, or segment. |
| `06_ranking_analysis.sql` | Generating top-N / bottom-N analysis for customers or products. |
| `07_change_over_time_analysis.sql` | Year-over-year and month-over-month growth and decline trends. |
| `08_cumulative_analysis.sql` | Running totals, moving averages, and progressive performance tracking. |
| `09_performance_analysis.sql` | Evaluating performance by department, region, or time period. |
| `10_data_segmentation.sql` | Customer or product segmentation using business logic conditions. |
| `11_part_to_whole_analysis.sql` | Share-of-total analysis to identify contribution breakdowns. |
| `12_report_customers.sql` | Aggregated customer-level metrics for reporting dashboards. |
| `13_report_products.sql` | Product-level performance summaries for business insights. |


---

## 🧩 Example Insights

Here are examples of insights the scripts are designed to reveal:
- Identify **top-performing regions or customer segments** based on revenue.  
- Track **monthly growth trends** and detect seasonal performance shifts.  
- Segment customers by **recency, frequency, and monetary (RFM)** behavior.  
- Compare **year-over-year metrics** to evaluate long-term performance.  
- Measure **churn and retention** patterns for customer lifecycle analysis.

---

## ⚙️ Tech Stack
- **Database:** PostgreSQL  
- **Language:** SQL  
- **Environment:** DBeaver / pgAdmin / SQL Workbench  
- **Data Source:** Simulated warehouse data (Post-ETL)

---

## 🔗 Repository Purpose
This project serves as a **reference library** for SQL analytical workflows.  
#### 🙌 Acknowledgment
This project was inspired by an educational SQL walkthrough by **DataWithBarra** on YouTube.  
I followed along and implemented the scripts independently to deepen my understanding of SQL analytics workflows and business data exploration.

---

## 🧠 Author
**AM MICH**  
Strategic Business Intelligence & Growth Consultant  
Transforming complex data into strategy, clarity, and measurable growth.  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-AM--MICH-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/your-linkedin/)
