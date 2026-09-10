# 🛒 Grocery Chain Data Analysis

## 📌 Overview

This project analyzes grocery chain transaction data to understand sales performance, customer purchasing behavior, product performance, store performance, discounts, and loyalty points.

The project uses Python for data analysis and Power BI to create an interactive dashboard for visualizing key business metrics and insights.

---

## 🎯 Objectives

* Analyze overall grocery sales performance.
* Identify top-performing stores.
* Identify best-selling products and aisles.
* Analyze customer purchasing patterns.
* Analyze discounts and their impact on sales.
* Analyze loyalty points.
* Identify sales trends over time.
* Create an interactive Power BI dashboard.
* Generate meaningful business insights.

---

## 📊 Dataset

The dataset contains **1,980 grocery transactions** with 11 columns.

### Main Features

* `customer_id`
* `store_name`
* `transaction_date`
* `aisle`
* `product_name`
* `quantity`
* `unit_price`
* `total_amount`
* `discount_amount`
* `final_amount`
* `loyalty_points`

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Power BI
* Power Query
* DAX
* Git & GitHub

---

## 🔄 Project Workflow

```text
Raw Dataset
    ↓
Data Cleaning
    ↓
Data Transformation
    ↓
Exploratory Data Analysis
    ↓
Power BI Data Modeling
    ↓
DAX Measures
    ↓
Interactive Dashboard
    ↓
Business Insights
```

---

## 🧹 Data Cleaning & Preparation

The dataset was prepared for analysis by:

* Checking data types.
* Checking missing values.
* Checking duplicate records.
* Converting transaction dates.
* Validating numerical fields.
* Preparing categorical variables.
* Creating calculated measures for Power BI.

---

# 📈 Power BI Dashboard

An interactive Power BI dashboard was developed to analyze grocery chain performance.

### Key KPIs

* Total Sales
* Total Transactions
* Total Quantity Sold
* Total Discount
* Average Transaction Value
* Total Loyalty Points

### Dashboard Visualizations

* Sales Trend by Date
* Sales by Store
* Sales by Aisle
* Top Products
* Quantity Sold by Product
* Discount Analysis
* Loyalty Points Analysis
* Customer Analysis
* Interactive Slicers

### Filters / Slicers

* Store Name
* Aisle
* Product Name
* Transaction Date

---

## 🧮 DAX Measures

### Total Sales

```DAX
Total Sales =
SUM('Grocery Data'[final_amount])
```

### Total Transactions

```DAX
Total Transactions =
COUNTROWS('Grocery Data')
```

### Total Quantity

```DAX
Total Quantity =
SUM('Grocery Data'[quantity])
```

### Total Discount

```DAX
Total Discount =
SUM('Grocery Data'[discount_amount])
```

### Average Transaction Value

```DAX
Average Transaction Value =
DIVIDE(
    [Total Sales],
    [Total Transactions]
)
```

### Total Loyalty Points

```DAX
Total Loyalty Points =
SUM('Grocery Data'[loyalty_points])
```

---

## 💡 Key Insights

The analysis helps identify:

* High-performing stores.
* Best-selling products.
* Popular grocery aisles.
* Customer purchasing patterns.
* Sales trends.
* Discount patterns.
* Loyalty program activity.
* Opportunities to improve sales performance.

---

## 📁 Project Structure

```text
Grocery-Chain-Data-Analysis/
│
├── data/
│   └── grocery_chain_dataset.csv
│
├── notebooks/
│   └── Grocery_Chain_Analysis.ipynb
│
├── powerbi/
│   └── Grocery Chain Data Analysis.pbix
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```


## 📚 Skills Demonstrated

* Data Analysis
* Data Cleaning
* Data Visualization
* Python
* Pandas
* Power Query
* Power BI
* DAX
* KPI Development
* Sales Analysis
* Customer Analysis
* Business Intelligence
* Dashboard Development
* Data Storytelling
* Git & GitHub

---

## 👩‍💻 Author

**Saranya Chandran.S**

Data Analyst | Data Scientist

