# 📊 Amazon Sales Analysis — End-to-End Power BI Project

## 🔍 Project Objective
The goal of this project is to analyze Amazon sales performance using an end-to-end Business Intelligence approach. The dashboard helps track overall business KPIs, regional sales trends, product-level performance, and customer behavior to support data-driven business decisions.

---

## 🗂 Dataset Source
The dataset used in this project was provided as part of a course and originally sourced from Kaggle. It represents an e-commerce business scenario including orders, revenue, product, customer, and regional information.

---

## 🏗 Data Modeling & Preparation
- Data was already clean and structured.
- Date hierarchy was created to analyze trends by:
  - Start of Month
  - Month
  - Year
- Star schema data model implemented:
  - 2 Fact tables
  - 8 Dimension tables
- Relationships created between fact and dimension tables for efficient analysis.
- A dedicated **Measures Table** was created using DAX to store calculated measures.

---

## 🧮 DAX Measures
- Created **30+ DAX measures** including:
  - Total Revenue
  - Total Orders
  - Total Profit
  - Total Returns
  - Return Rate
  - Target vs Actual metrics
  - Time-intelligence calculations
- Measures are organized in a separate Measures Table for better model management and readability.

---

## 🧭 User Experience Features
- Navigation button strip available on all dashboards to easily switch between pages.
- Interactive slicers and cross-filtering enabled across visuals.
- Drill-through functionality implemented from Executive Dashboard to Product Details.

---

## 📈 Dashboard Pages

### 1️⃣ Executive Dashboard
Provides a high-level business overview with key KPIs and trends.

**Includes:**
- KPI Cards:
  - Total Revenue
  - Total Orders
  - Total Profit
  - Return Percentage
- Monthly Revenue trend (Start of Month based)
- Orders by Category (Accessories, Bikes, Clothing) with custom tooltip page
- Top 10 Products table showing:
  - Revenue
  - Orders
  - Profit
  - Grand totals for each metric
- Monthly KPIs at bottom:
  - Monthly Revenue
  - Monthly Orders
  - Monthly Returns
- Most sold product type
- Most returned product type

---

### 2️⃣ Map / Region Analysis Dashboard
Focuses on geographical performance of orders.

**Includes:**
- Map visualization showing **Total Orders by Country**
- Continent-based slicer:
  - Europe
  - North America
  - Pacific
- Allows easy comparison of regional performance

---

### 3️⃣ Product Details Dashboard
Provides deep insights into product-level performance and target tracking.

**Product Metrics:**
- Total Orders
- Total Revenue
- Total Profit
- Total Returns
- Return Rate

**Visuals:**
- Time series trends (Start of Month) for each metric
- Gauge Charts:
  - Monthly Orders vs Target
  - Monthly Revenue vs Target
  - Monthly Profit vs Target

**Advanced Feature:**
- Drill-through enabled from Executive Dashboard
- Selecting a product from Top 10 table shows detailed product performance in this page

---

### 4️⃣ Customer Analysis Dashboard
Analyzes customer behavior and revenue contribution.

**Filters:**
- Year slicer (2020, 2021, 2022)

**Donut chart:**
- Orders by Income Level
- Orders by Occupation

**KPIs:**
- Unique Customers
- Revenue per Customer

**Trends:**
- Revenue per Customer over time using date hierarchy

**Tables & Labels:**
- Top 100 Customers by Orders and Revenue
- Customer label section showing:
  - Customer name
  - Skill level
  - Total revenue
- Additional KPIs:
  - Total Orders
  - Highest Revenue by Customer
  - Total Revenue

**Interactivity:**
- Multiple visuals connected through filters and cross-highlighting

---

## ⭐ Featured Analysis Pages
- **Q&A Visual:** Allows natural language queries on dataset
- **Decomposition Tree:** Breaks down KPIs to identify performance drivers
- **Key Influencers:** Identifies factors affecting revenue and returns
- **Custom Tooltip:** Provides contextual insights on hover in Executive Dashboard

---

## 💡 Key Business Insights
- Accessories category generates the highest number of orders.
- North America contributes the majority of total orders compared to other continents.
- Some products (e.g., water bottles) show high sales volume but also higher return rates.
- Revenue per customer changes significantly across different years, indicating shifting customer value trends.

---

## 🎯 Business Value
This dashboard can help business stakeholders to:
- Identify high-performing and under-performing regions
- Monitor product performance against business targets
- Reduce returns by analyzing problematic products
- Improve customer segmentation and marketing strategies
- Track monthly and yearly growth trends

---

## 📁 Repository Structure

Amazon-Sales-Analysis-PowerBI  
│  
├── Dataset  
│   └── (Dataset file)  
│  
├── PowerBI_File  
│   └── Amazon_Sales_Dashboard.pbix  
│  
├── Screenshots  
│   ├── Executive_Dashboard.png  
│   ├── Map_Analysis.png  
│   ├── Product_Details.png  
│   └── Customer_Analysis.png  
│  
└── README.md  

---

## 🚀 Future Enhancements
- Add forecasting using time-series models
- Add customer lifetime value (CLV) analysis
- Implement profit margin optimization insights
- Integrate real-time data sources

---

## 🧠 Skills Demonstrated
- Data Modeling (Star Schema)
- DAX Measure Creation
- Business KPI Design
- Dashboard UX & Navigation
- Drill-Through & Tooltips
- Interactive Filtering
- Business Storytelling with Data
