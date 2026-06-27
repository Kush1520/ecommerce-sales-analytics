# 📊 E-Commerce Executive Dashboard | Tableau

Interactive business intelligence dashboard developed using Tableau Public to analyze sales, profit, customers, orders, margins, and category-wise business performance.

---

## 🚀 Features

- KPI Cards
  - Total Sales
  - Total Profit
  - Total Orders
  - Total Customers
  - Profit Margin

- Monthly Sales Trend Analysis

- Category-wise Sales Distribution

- Regional Profit Analysis

- Interactive Filters
  - Region
  - Category
  - Segment

---

## 🛠 Tools Used

- Tableau Public
- Sample Superstore Dataset
- Git
- GitHub

---

## 🔍 Analysis Performed

The following analyses were conducted using Tableau:

### 1. Sales Analysis
- Computed total sales generated.
- Examined monthly sales trends.
- Identified periods with peak and low sales.

### 2. Profit Analysis
- Calculated overall profit.
- Analyzed profit contribution by region.
- Compared profitability across regions.

### 3. Customer Analysis
- Calculated distinct customer count.
- Assessed customer reach and engagement.

### 4. Order Analysis
- Calculated total number of orders.
- Evaluated order volume performance.

### 5. Margin Analysis
- Derived Profit Margin using:

```text
Profit Margin = SUM(Profit) / SUM(Sales)
```

- Formatted margin as percentage.

### 6. Category Contribution Analysis
- Measured sales share by category.
- Visualized contribution using a pie chart.
- Converted values into percentage of total sales.

### 7. Interactive Filtering
Implemented filters for:

- Region
- Segment
- Category

to allow dynamic dashboard exploration.

---

## ⚙ Methodology

The project followed the following workflow:

### Step 1 — Data Acquisition
Imported the Sample Superstore dataset into Tableau.

### Step 2 — Data Understanding
Reviewed dimensions such as:

- Category
- Region
- Segment
- Customer ID
- Order Date

Measures:

- Sales
- Profit
- Quantity

### Step 3 — KPI Development

Created KPI worksheets for:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Profit Margin

### Step 4 — Trend Analysis

Constructed Monthly Sales Trend using:

Order Date → Month

Sales → Line Chart

### Step 5 — Regional Analysis

Built bar charts to evaluate:

Profit by Region

### Step 6 — Category Analysis

Developed:

Category Sales Comparison

Category Share Pie Chart

### Step 7 — Dashboard Assembly

Combined worksheets into an executive dashboard layout consisting of:

• Header Section

• KPI Cards

• Monthly Trend Visualization

• Regional Profit Analysis

• Category Share Visualization

• Interactive Filters


### Step 8 — Dashboard Formatting

Applied:

- Entire View fitting
- Consistent color palette
- Dynamic filtering
- Responsive layout
- Label formatting
- Percentage formatting


---

## 📈 Dashboard Preview

![Dashboard](images/dashboard.png)

---

## 📂 Project Structure

```text
ecommerce-sales-analytics/

├── dashboard/
│   └── Ecommerce_Executive_Dashboard.twbx

├── data/
│   └── Sample - Superstore.csv

├── images/
│   └── dashboard.png

├── notebooks/

├── reports/

├── sql/

├── src/

├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📊 Key Insights

- Technology contributes the highest share of sales.
- West region generates the maximum profit.
- Sales show an upward trend toward the end of the year.
- Profit margin achieved: **12.47%**

---

## 🎯 Key Insights

Technology contributes the highest percentage of total sales.

West Region generates the highest profit.

Sales demonstrate strong growth towards the end of the year.

The overall profit margin achieved is **12.47%**.

---

## 🚀 Future Improvements

Potential enhancements include:

- Profit forecasting
- Customer segmentation analysis
- Geographic sales maps
- Product-level profitability analysis
- Time-series forecasting models

---

## 💾 Tableau Workbook

The complete Tableau workbook is available in:

```text
dashboard/Ecommerce_Executive_Dashboard.twbx
```

---

## 👨‍💻 Author

**Krrish Gagneja**

BE Information Technology  
UIET, Panjab University

GitHub:
https://github.com/Kush1520/ecommerce-sales-analytics/tree/main/ecommerce-sales-analytics