## 📌 Air-Cargo-SQL-Analysis
SQL-based analysis of air cargo operations to evaluate delays, capacity utilization, route revenue, and service performance. Demonstrates data modeling, analytical querying, and supply chain performance insights using structured airline cargo datasets.

## 🛠 Tools Used
* SQL- Data querying and analysis
* PostgreSQL / MySQL / SQL Server – Database management
* GitHub - Version control and project documentation
* Data modeling concepts

## 🗂 Database Schema
- The project uses a relational database structure to model air cargo operations. It consists of three main tables: airlines, airports, and flights.
  
* airlines – Contains airline company details.
* airports – Stores airport location information, including airport codes, cities, and countries.
* flights – Holds operational flight data such as cargo weight, capacity, revenue, and delays.

## ❓ Business Questions
- This analysis explores key operational questions related to air cargo logistics and supply chain performance:
  
* What percentage of flights arrive on time?
* Which airlines experience the highest average delays?
* Which routes generate the highest cargo revenue?
* How efficiently is cargo capacity utilized across flights?
* Are there patterns in delays that could impact service reliability?

## 🧠 Key SQL Techniques Used
- The project demonstrates several essential SQL techniques commonly used in data analytics:
  
* Joins to combine airline, airport, and flight datasets
* Aggregate functions such as SUM, AVG, and COUNT
* GROUP BY for route and airline performance analysis
* CASE statements to categorize on-time and delayed flights
* Derived metrics for calculating cargo capacity utilization
* Sorting and filtering to identify top-performing routes and airlines

## 📊 Key Insights from the Analysis
- The analysis reveals several insights into air cargo operations:
  
* Certain routes generate higher cargo revenue, indicating strong trade lanes.
* Some airlines show higher average delays, which may affect service reliability.
* Cargo capacity utilization varies across flights, suggesting potential efficiency improvements.
* On-time performance metrics highlight areas where operational processes could be optimized.

## 📈 Supply Chain KPIs Calculated in This Project
- This project calculates several key performance indicators (KPIs) commonly used in supply chain and logistics operations to evaluate efficiency and service quality.

On-Time Performance Rate
* Measures the percentage of flights that arrive without delays. This KPI reflects operational reliability and service quality.

Average Delay Time
* Calculates the average delay experienced by flights, helping identify operational bottlenecks and performance issues.

Cargo Capacity Utilization
* Measures how efficiently aircraft cargo space is used by comparing cargo weight to total capacity.

Revenue by Route
* Analyzes total cargo revenue generated across origin–destination routes to identify high-performing trade lanes.

Flight Volume by Airline
* Tracks the number of flights operated by each airline to understand operational scale and workload distribution.

## 📁 Project Structure
```text
Air-Cargo-SQL-Analysis
│
├── data
│   └── air_cargo_sample_data.sql
│
├── queries
│   └── analysis_queries.sql
│
├── insights
│   └── business_insights.md
│
└── README.md
