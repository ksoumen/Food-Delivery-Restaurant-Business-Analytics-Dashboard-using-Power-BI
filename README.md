# 🍽️ Food Delivery & Restaurant Business Analytics Dashboard using Power BI

An end-to-end **Power BI Business Intelligence project** designed to analyze food delivery and restaurant business performance. The project transforms raw operational, customer, restaurant, and order data into interactive dashboards using **Power BI, DAX, Power Query, data modeling, and time intelligence**.

The dashboard provides insights into **sales, customers, restaurants, delivery operations, order status, revenue trends, and business KPIs**.

---

## 📌 Project Overview

The objective of this project is to build an interactive Business Intelligence solution that helps stakeholders monitor restaurant and food delivery performance and identify actionable business insights.

### Business Objectives

- Monitor overall business performance
- Track revenue and order KPIs
- Analyze customer behavior
- Compare new and repeat customers
- Evaluate restaurant performance
- Analyze restaurant ratings and cuisines
- Monitor delivery performance
- Identify late and cancelled orders
- Analyze city-wise operational performance
- Track revenue and order trends over time
- Provide interactive drill-through analysis

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Data Modeling**
- **Star Schema**
- **Time Intelligence**
- **Interactive Data Visualization**

---

## 📂 Dataset

The project uses restaurant, customer, order, and date-related data.

### Main Tables

- **Orders** – Order-level transactional information
- **Customers** – Customer information and customer types
- **Restaurants** – Restaurant information, cuisine, rating, cost, and location
- **DateTable** – Date dimension used for time-based analysis
- **KPI** – KPI selection table used for dynamic analysis

---

# 📊 Dashboard Pages

The Power BI report contains six major analytical pages.

---

## 1️⃣ Executive Overview

The Executive Overview provides a high-level summary of the food delivery business.

### Key Metrics

- Total Orders
- Total Revenue
- Average Order Value
- Average Delivery Time
- Revenue Trends
- Order Trends
- Revenue by City
- Top Restaurants
- Order Status Breakdown

### Screenshot

![Executive Overview](Executive%20Overview%20Screen%20Shot.png)

---

## 2️⃣ Customer Analytics

This page focuses on customer behavior and customer segmentation.

### Key Analysis

- New vs Repeat Customers
- Orders by Customer Type
- Customer Signup Trend
- Top Customers
- Repeat Customer %
- Orders per Customer
- Customer-level revenue and order analysis

### Screenshot

![Customer Analytics](Customer%20Analytics%20Screen%20Shot.png)

---

## 3️⃣ Restaurant Performance

This page evaluates restaurant-level performance and business contribution.

### Key Analysis

- Revenue by Restaurant
- Orders by Cuisine
- Average Restaurant Rating
- Average Votes
- Revenue per Restaurant
- Cost Bucket Analysis
- Rating Distribution
- Top Performing Restaurants

### Screenshot

![Restaurant Performance](Restaurant%20Performance%20Screen%20Shot.png)

---

## 4️⃣ Delivery & Operations

This page focuses on delivery efficiency and operational performance.

### Key Analysis

- Delivery Status Breakdown
- City-wise Delivery Time
- Cancellation by City
- Late Orders
- Cancelled Orders
- Late Delivery %
- Average Delivery Time
- Delivered Orders

### Screenshot

![Delivery & Operations](Delivery%20and%20Operation%20Screen%20Shot.png)

---

## 5️⃣ Advanced Insights

This page provides deeper interactive analysis using dynamic KPI selection and advanced visualizations.

### Key Analysis

- Dynamic KPI Selection
- Average Delivery Time
- Orders
- Average Order Value
- Revenue
- Revenue Trends
- Delivery Time Trends
- Cost Bucket Analysis
- Bubble Chart Analysis

### Screenshot

![Advanced Insights](Advanced%20insights%20Screen%20Shot.png)

---

## 6️⃣ Restaurant Details

The Restaurant Details page provides detailed restaurant-level analysis using **drill-through functionality**.

### Key Analysis

- Restaurant-specific KPIs
- Total Orders
- Total Revenue
- Average Delivery Time
- Average Rating
- Orders by Cuisine
- Orders by Customer Type
- Delivery Status
- Revenue Trend
- Order Trend

### Screenshot

![Restaurant Details](Restaurant%20Details%20Screen%20Shot.png)

---

# 🧩 Data Model

The project follows a structured **Star Schema** approach.

### Model Components

- **Orders** – Fact table
- **Customers** – Dimension table
- **Restaurants** – Dimension table
- **DateTable** – Date dimension
- **KPI** – Supporting table for dynamic KPI analysis

### Data Model Screenshot

![Data Model](Data%20Model%20Screen%20Shot.png)

---

# 📐 DAX Measures

The project contains multiple DAX measures organized into logical categories for easier maintenance and analysis.

## 👥 Customer Measures

Includes measures related to customer behavior:

- Filter City
- Repeat vs New Customer
- Repeat Customer
- Repeat Customer %
- Orders per Customer

### Measure Screenshots

![Filter City Measure](Measures%20Screenshot/Customer%20Table%20Measures/Filter%20City%20Measure.png)

![Repeat vs New Customer](Measures%20Screenshot/Customer%20Table%20Measures/Repeat%20vs%20New%20Measure.png)

---

## 📊 KPI Measures

KPI measures are used to create dynamic KPI analysis across the dashboard.

### Includes

- KPI Measure
- Selected KPI Value
- Dynamic KPI selection

### Measure Screenshots

![KPI Measure](Measures%20Screenshot/KPI/KPI%20Measure.png)

![Selected KPI Value](Measures%20Screenshot/KPI/Selected%20KPI%20Value%20Measure.png)

---

## 📦 Order & Business KPI Measures

Measures are used to calculate core business metrics.

### Includes

- Total Orders
- Total Revenue
- Total Customers
- Total Restaurants
- Average Order Value
- Average Delivery Time
- Revenue per Restaurant
- Average Rating
- Average Votes

### Measure Screenshots

![Average Delivery Time](Measures%20Screenshot/Orders%20Table%20Measures/2.KPI%20Measures/Avg%20Delivery%20Time%20Measure.png)

![Average Order Value](Measures%20Screenshot/Orders%20Table%20Measures/2.KPI%20Measures/Avg%20Order%20Value%20Measure.png)

![Total Customers](Measures%20Screenshot/Orders%20Table%20Measures/2.KPI%20Measures/Total%20Customer%20Measure.png)

![Total Orders](Measures%20Screenshot/Orders%20Table%20Measures/2.KPI%20Measures/Total%20Orders%20Measure.png)

![Total Revenue](Measures%20Screenshot/Orders%20Table%20Measures/2.KPI%20Measures/Total%20Revenue%20Measure.png)

---

## 🚚 Status Measures

These measures analyze delivery and order status.

### Includes

- Delivered Orders
- Cancelled Orders
- Late Orders
- Late Delivery %
- Cancellation %

### Measure Screenshots

![Cancelled Orders](Measures%20Screenshot/Orders%20Table%20Measures/4.Status%20Measures/Cancelled%20Order%20Measure.png)

![Delivered Orders](Measures%20Screenshot/Orders%20Table%20Measures/4.Status%20Measures/Delivered%20Orders%20Measure.png)

![Late Orders](Measures%20Screenshot/Orders%20Table%20Measures/4.Status%20Measures/Late%20Orders%20Measure.png)

![Late Delivery Percentage](Measures%20Screenshot/Orders%20Table%20Measures/4.Status%20Measures/Late%20Delivery%20%25%20Measure.png)

---

## ⏱️ Time Intelligence Measures

Time intelligence is used to analyze business performance across different periods.

### Includes

- Revenue YTD
- Previous Month Revenue
- Revenue Growth %

### Measure Screenshots

![Revenue Growth](Measures%20Screenshot/Orders%20Table%20Measures/5.Time%20Intelligence%20Measures/Revenue%20Growth%20%25%20Measure.png)

![Previous Month Revenue](Measures%20Screenshot/Orders%20Table%20Measures/5.Time%20Intelligence%20Measures/Revenue%20Previous%20Month%20Measure.png)

![Revenue YTD](Measures%20Screenshot/Orders%20Table%20Measures/5.Time%20Intelligence%20Measures/Revenue%20YTD%20Measure.png)

---

# 🎯 Key Features

- ✅ Interactive Power BI Dashboard
- ✅ Executive Business Overview
- ✅ Customer Analytics
- ✅ Restaurant Performance Analysis
- ✅ Delivery & Operations Analysis
- ✅ Advanced Business Insights
- ✅ Restaurant Drill-through Analysis
- ✅ Dynamic KPI Selection
- ✅ DAX Measures
- ✅ Time Intelligence
- ✅ Star Schema Data Model
- ✅ Interactive Filters
- ✅ Business KPI Tracking
- ✅ Revenue & Order Trend Analysis
- ✅ Customer Segmentation
- ✅ City-wise Analysis

---

# 📁 Repository Structure

```text
Food-Delivery-Restaurant-Business-Analytics-Dashboard-using-Power-BI/
│
├── Dashboard Screenshots/
│   ├── Executive-Overview.png
│   ├── Customer-Analytics.png
│   ├── Restaurant-Performance.png
│   ├── Delivery-Operations.png
│   ├── Advanced-Insights.png
│   ├── Restaurant-Details.png
│   └── Data-Model.png
│
├── Measures Screenshot/
│   │
│   ├── Customer Table Measures/
│   │   ├── Filter City Measure.png
│   │   └── Repeat vs New Measure.png
│   │
│   └── Orders Table Measures/
│       │
│       ├── 1.Customer Measures/
│       ├── 2.KPI Measures/
│       ├── 3.Resturant Performance Measures/
│       ├── 4.Status Measures/
│       └── 5.Time Intelligence Measures/
│
├── dataset.xlsx
│
└── README.md
```

---

# 📈 Business Insights

The dashboard enables stakeholders to identify:

- Overall revenue and order performance
- Customer retention through repeat customer analysis
- Restaurant contribution to total revenue
- High-performing cuisines
- Delivery efficiency across cities
- Late and cancelled order patterns
- Restaurant rating and popularity trends
- Revenue growth and month-over-month performance
- Operational areas requiring improvement

---

# 🚀 Project Highlights

| Area | Implementation |
|---|---|
| BI Tool | Power BI |
| Data Transformation | Power Query |
| Calculations | DAX |
| Data Modeling | Star Schema |
| Time Analysis | Time Intelligence |
| Customer Analysis | New vs Repeat Customers |
| Operations | Delivery & Cancellation Analysis |
| Restaurant Analysis | Revenue, Rating & Cuisine |
| Interactivity | Filters, Buttons & Drill-through |
| KPI Analysis | Dynamic KPI Selection |

---

# 💡 Skills Demonstrated

This project demonstrates practical skills in:

- Business Intelligence
- Data Analysis
- Power BI
- DAX
- Power Query
- Data Modeling
- Star Schema Design
- Time Intelligence
- KPI Development
- Dashboard Design
- Customer Analytics
- Restaurant Analytics
- Operational Analytics
- Data Visualization

---

# 👨‍💻 Author

## Soumen Karmakar

**B.Tech – Computer Science & Business Systems**

**Data Analyst | Power BI | SQL | Python | Excel**

### Skills

`Power BI` `DAX` `SQL` `Python` `Excel` `Pandas` `Data Analytics` `Data Visualization`

---

## ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ **Star**.

---

**Built with Microsoft Power BI**
