# 🚴‍♂️ Sales Performance Analysis

Welcome to my Power BI dashboard project designed for a manufacturing company specializing in **cycling equipment**. This interactive report was built to empower the executive and analytics teams with actionable insights, track performance KPIs, and support data-driven decisions across product lines and regions.

[Sales Performance Deep Dive Dashboard](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/Sales%20Performance%20Deep%20Dive%20Dashboard%20(Power%20BI%20Only).pbix)

> 🧠 **Objective**: To enable the management team to monitor revenue trends, customer segmentation, return rates, and regional performance through a clean, intuitive Power BI interface.

---

## 📊 Dashboard Overview

The dashboard is structured into **four main pages**, each with a distinct analytical focus:

### 1. 🏆 Executive Dashboard
- High-level KPIs: Revenue, Orders, Profit, Return Rate
- Monthly comparisons (Current vs Previous Month)
- Top-performing products
- Revenue trends (line chart) and orders by category (bar chart)
- Custom tooltips for deeper insight

### 2. 🗺️ Map Visualization
- Global view of order volumes
- Interactive map showing total orders by country
- Continent-level filtering

### 3. 📦 Product Details
- Detailed product-level analysis
- Profit margins, revenue trends, and order volume
- Gauge charts for monthly performance vs targets
- Interactive slicer panel for filtering by category/subcategory

### 4. 👥 Customer Details
- Customer segmentation by occupation and income
- Average revenue per customer, trends over time
- Donut charts and slicers for dynamic filtering

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)** for custom measures and KPIs
- **Power Query** for data cleansing and transformation
- **Data Model**: Snowflake Schema
  - Central **Sales Fact Table** (2020, 2021, 2022 data appended)
  - Supporting **lookup tables**: Calendar, Customer, Product (with categories), Territory, Returns

---

## 🧱 Project Structure

| **Component**     | **Details**                                              |
|-------------------|----------------------------------------------------------|
| **📁 Data Sources** |                                                          |
|                   | ├── AdventureWorks [Sales Data 2020](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/AdventureWorks%20Sales%20Data%202020.csv) / [Sales Data 2021](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/AdventureWorks%20Sales%20Data%202021.csv)/ [Sales Data 2022](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/AdventureWorks%20Sales%20Data%202022.csv)        |
|                   | ├── [Calendar Lookup](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/AdventureWorks%20Calendar%20Lookup.csv)                                      |
|                   | ├── [Customer Lookup](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/AdventureWorks%20Customer%20Lookup.csv)                                       |
|                   | ├── [Product Categories](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/AdventureWorks%20Product%20Categories%20Lookup.csv) / [Subcategories Lookup](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/AdventureWorks%20Product%20Subcategories%20Lookup.csv)            |
|                   | ├── [Product Lookup](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/AdventureWorks%20Product%20Lookup.csv)                                        |
|                   | ├── [Territory Lookup](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/AdventureWorks%20Territory%20Lookup.csv)                                      |
|                   | └── [Returns Data](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/AdventureWorks%20Returns%20Data.csv)                                          |
| **📊 Power BI File** |                                                          |
|                   | └── [Sales Performance Deep Dive Dashboard](https://github.com/DivyanshuDS18/-Sales-Performance-Deep-Dive-Dashboard-Power-BI-Only-/blob/main/Sales%20Performance%20Deep%20Dive%20Dashboard%20(Power%20BI%20Only).pbix)    |



---

## 🚀 How to Use

1. **Open the `.pbix` file** using Power BI Desktop.
2. **Review the data model** to explore relationships and transformations.
3. **Navigate** between pages using the tabs at the bottom or page navigation buttons.
4. Use **slicers and filters** to interact with the data and drill into specific insights.
5. To refresh with new data (if connected), go to **Home > Refresh**.

---
