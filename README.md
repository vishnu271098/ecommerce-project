# 📊 Ecommerce Analytics Project (SQL + Power BI)

This project demonstrates end-to-end data analysis using **MySQL**, **Power BI**, and **CSV datasets**.  
It includes SQL queries for data exploration, transformations, and analytics — along with a dashboard built in Power BI.

---

## 📁 Project Structure

ecommerce-project/
│
├── data/
│ ├── ecommerce_customers.csv
│ ├── ecommerce_orders.csv
│ └── ecommerce query results.xlsx
│
├── sql/
│ └── queries.sql
│
├── pbi/
│ ├── Dashboard preview.png
│ └── README.md
│
└── README.md

---

## 🛠️ Tools Used

- **MySQL** → Data extraction, cleaning, and analysis  
- **Power BI Desktop** → Data modeling + dashboard creation  
- **Excel / CSV** → Source datasets  
- **GitHub** → Project hosting and versioning  

---

## 📌 SQL Topics Covered

The `queries.sql` file includes:

- Aggregations (SUM, COUNT, AVG)  
- GROUP BY analytics  
- Customer-level metrics  
- Category-level performance  
- Order insights
- Key Metrics Analysis

---

## 📸 Dashboard Preview (Power BI)

The full PBIX file is not uploaded due to size restrictions.  
A screenshot preview is available here:

📂 `pbi/Dashboard preview.png`

---

## 📥 How to Use This Project

### **1. Import SQL data**
Load the CSV files into MySQL:

```sql
LOAD DATA LOCAL INFILE 'ecommerce_customers.csv'
INTO TABLE customers
FIELDS TERMINATED BY ','
ENCLOSED BY '"'
IGNORE 1 LINES;
