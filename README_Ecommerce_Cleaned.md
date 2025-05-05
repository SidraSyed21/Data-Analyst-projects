
# 🛒 End-to-End Data Engineering: E-commerce Sales Project

## 🚀 Overview
This project demonstrates an end-to-end data engineering solution on e-commerce sales data — from ETL to data warehousing to interactive dashboards using Power BI.

---

## 🛠 Tech Stack
- **Python**: Data Extraction, Cleaning, Transformation
- **SQL Server**: Data Warehousing with Star Schema
- **Power BI**: Data Visualization
- **Pandas, pyodbc, SQLAlchemy**

---

## 📁 Folder Structure
```
├── data/
│   └── ecommerce_sales.csv
├── etl/
│   └── etl_script.py
├── sql/
│   └── create_tables.sql
├── dashboards/
│   └── ecommerce_dashboard.pbix
└── README.md
```

---

## 🔄 ETL Process

### 1. Extract
Load raw data from CSV using Python (Pandas).

### 2. Transform
- Clean missing or incorrect data
- Parse dates, calculate revenue, etc.

### 3. Load
- Create fact and dimension tables
- Insert into SQL Server using `pyodbc`

---

## 🧱 Data Modeling (Star Schema)
**Fact Table:**
- Fact_Sales (Order_ID, Product_ID, Date_ID, Customer_ID, Quantity, Revenue)

**Dimension Tables:**
- Dim_Product (Product_ID, Name, Category)
- Dim_Date (Date_ID, Date, Month, Quarter)
- Dim_Customer (Customer_ID, Name, Region)

---

## 📊 Power BI Dashboards

Key metrics include:
- Sales Trends
- Top Products
- Regional Performance
- Profit Margins

---

## ✅ Results & Insights
- Achieved reusable, scalable data pipeline
- Enabled visual, insight-driven business reporting

---

## 🔧 Future Enhancements
- Automate ETL with Apache Airflow
- Move to cloud (Azure SQL, Data Factory)
- Add predictive analytics with ML

---

## 📌 License
This project is open-source and available under the MIT License.
