# 📊 US Sales & Customer Behavior Dashboard (2020–2023)

**Author**: Fatima Aboura  
**Project**: Data Visualization & Dashboarding  
**Tools Used**: Metabase, SQL, Data Preprocessing Tools  

---

## 📌 Project Overview

This project involves analyzing US sales and customer behavior data from 2020 to 2023. The main objective is to build **interactive dashboards** that help stakeholders gain insights into sales performance and customer engagement trends.

---

## 🗂️ Database Schema

The dataset includes the following tables:

- **Fact Table**
  - `Orders`: Contains sales, profit, and quantity data (converted to numerical format).
  
- **Dimension Tables**
  - `Customers`: Information about each customer.
  - `Locations`: Geographic data (region, state, city).
  - `Products`: Product details including category and subcategory.

**Table Relationships**:  
Standard star schema connecting the fact table to dimensions via foreign keys.

---

## ⚙️ Data Preprocessing

- Replaced commas with periods to convert text-based numerical fields (sales, profit, quantity) into actual numbers.
- Performed **exploratory data visualization** to understand trends and outliers before building dashboards.

---

## 📈 Dashboards & Analysis

### 1. **Customer Dashboard**

**Purpose**:  
To provide insights into customer behaviors, loyalty, segmentation, and trends over time.

**Key Features**:
- **KPI Overview**: Total customers, total sales per customer, number of orders (current vs. previous year).
- **Customer Trends**: Monthly trend analysis to spot seasonality.
- **Customer Distribution**: Based on number of orders to assess engagement.
- **Top 10 Customers by Profit**: Including rank, sales, profit, and last order date.

---

### 2. **Sales Dashboard**

**Purpose**:  
To evaluate year-over-year sales performance and identify profitable product lines and time periods.

**Key Features**:
- **KPI Overview**: Total sales, profit, quantity (current vs. previous year).
- **Monthly Sales Trends**: With visual highlights for peak and low-performing months.
- **Product Subcategory Comparison**: Profit and sales breakdown.
- **Weekly Trends**: Weekly averages and deviation markers for sales and profits.

---

## 🧩 Design & Interactivity Requirements

- **Year Selector**: Dynamic year filter for historical analysis.
- **Cross-navigation**: Seamless dashboard transitions.
- **Interactive Charts**: Clickable/filterable graphs and KPIs.
- **Flexible Filters**: Filter by product category/subcategory and by location (region, state, city).

---

## 🔎 Demo & Access

- **Demo available upon request**
- **For more info**:  
  📧 hello@reallygreatsite.com  
  🌐 [reallygreatsite.com](http://www.reallygreatsite.com)  
  📞 123-456-7890

---

## 🙏 Thanks!

