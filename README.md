



# 📊 Sales Analysis Project

## 🚀 Overview

This project focuses on analyzing sales data to extract meaningful insights and support data-driven decision-making. The dataset contains transactional records including order details, customers, regions, products, sales, cost, and profit.

The project demonstrates a complete data analytics workflow using **Python**, **MySQL**, and **Power BI**.

---

## 🧰 Tech Stack

* 🐍 **Python** – Data cleaning, preprocessing, and exploratory data analysis
* 🗄️ **MySQL** – Data storage and querying
* 📊 **Power BI** – Data visualization and dashboard creation

---

## 📁 Dataset Description

The dataset includes the following columns:

* `Order_ID` – Unique identifier for each order
* `Order_Date` – Date of the order
* `Customer` – Customer name
* `Region` – Sales region (North, South, East, West)
* `Product` – Product category (Laptop, Mobile, Tablet, Monitor, Printer)
* `Sales` – Revenue generated
* `Cost` – Cost incurred
* `Profit` – Profit earned (Sales - Cost)
* `Year` – Extracted year from date
* `Month` – Extracted month from date

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning & Preprocessing (Python)

* Removed inconsistencies and handled missing values
* Converted date columns into proper datetime format
* Extracted **Year** and **Month** from order date
* Verified and calculated profit values

---

### 2️⃣ Data Storage & Querying (MySQL)

* Imported cleaned dataset into MySQL database
* Created structured tables
* Wrote SQL queries to analyze:

  * Total sales by region
  * Product-wise performance
  * Monthly and yearly trends
  * Customer contribution

---

### 3️⃣ Data Visualization (Power BI)

* Built an interactive dashboard including:

  * 📌 Sales, Cost, and Profit overview
  * 🌍 Region-wise performance
  * 📦 Product category analysis
  * 📅 Monthly trends
  * 👥 Top customers

---

## 📈 Key Insights

* Identified top-performing **regions and products**
* Analyzed **seasonal trends** in sales
* Highlighted **high-value customers**
* Evaluated **profitability across categories**

---

## 🎯 Results

The project provides a clear visualization of business performance and helps in:

* Improving decision-making
* Identifying growth opportunities
* Optimizing sales strategies

---

## 📊 Dashboard Preview

*(Add your Power BI dashboard screenshot here)*

---

## ▶️ How to Run the Project

### Step 1: Python (Data Cleaning)

```bash
# Install required libraries
pip install pandas numpy matplotlib seaborn
```

### Step 2: MySQL

* Import dataset into MySQL
* Run SQL queries for analysis

### Step 3: Power BI

* Load dataset or connect to MySQL
* Build dashboard using visuals

---

## 📌 Future Improvements

* Add predictive analytics (sales forecasting)
* Automate ETL pipeline
* Deploy dashboard online
* Or design a **professional dashboard layout for Power BI**

