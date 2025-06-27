# 🧠 Sales Insights Dashboard (Power BI Project)

## 📌 Project Overview

This Power BI project focuses on building a performance-driven dashboard to help mid-level management track key sales metrics and derive actionable insights from sales data spanning three years (2020–2022).

![E-commerceproject-MadewithClipchamp-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/559e0746-5195-499b-9f52-63ee0144cf22)

### 🎯 Business Objective

The primary goal of this project is to empower **sales managers** with a well-structured, interactive dashboard that provides both **high-level KPIs** and **deep-dive analytics**, enabling them to:

- Monitor sales KPIs across all business dimensions
- Compare regional performance
- Analyze trends at the product level
- Identify and segment high-value customers

---

## 🧭 Project Workflow

### 1️⃣ Business Understanding

- Defined the business objective and the target audience: **sales managers**
- Outlined key performance questions and dashboard expectations
- Established project scope: performance tracking, customer profiling, and regional/product analysis

---

### 2️⃣ Data Exploration

- Explored all data tables to understand schema and relationships
- Identified key dimensions and facts relevant to business goals
- Evaluated table consistency across three yearly datasets (2020, 2021, 2022)

---

### 3️⃣ Data Cleaning (Power Query)

Performed comprehensive data preprocessing using **Power Query Editor**:

- Standardized and corrected **data types**
- Handled missing data by removing or imputing **null values**
- Engineered useful columns:
  - **Full Name** (concatenated)
  - **Age** (calculated from birthdate)
   
  ![some cleaning on customer table](https://github.com/user-attachments/assets/588c3c30-5a0e-4512-bf04-352c7ec3568b)

- **Merged** the three yearly sales datasets into a consolidated fact table
  
![some cleaning on customer table](https://github.com/user-attachments/assets/a1223a54-0063-4789-bcfd-d20c256f0521)

- Created a **calendar table** using `CALENDAR()` for robust time-based analysis
  
![some cleaning on customer table](https://github.com/user-attachments/assets/3f1830d0-6f35-493e-b1de-38021df2ed54)

---

### 4️⃣ Data Modeling

Designed a scalable **star schema** (with limited snowflake extensions where needed):

![some cleaning on customer table](https://github.com/user-attachments/assets/7c333c6b-12c3-4be1-afde-e225bfc46ee8)

- Established clear relationships between dimension and fact tables
- Created essential **DAX measures** and **calculated columns**, including:

  - `DIVIDE()` for safe division operations
  - `SUMX()` for row-context aggregations
  - `RELATED()` for pulling values across relationships
  - `DISTINCTCOUNT()` for unique counts
  - `CALCULATE()` with `DATEADD()` for time intelligence
  - KPIs for actual vs. target comparisons
  - **Field Parameters** and **Numeric Parameters** for dynamic visuals
    
![some cleaning on customer table](https://github.com/user-attachments/assets/602abf85-d7d5-4f59-8896-0f7967450a22)

---

### 5️⃣ Dashboard Design & UX

Focused on clear, user-centered visualization for decision-makers:

- Developed a consistent **color palette** and professional layout
- Structured the report into multiple logical **pages** (e.g., KPIs, Region Comparison, Product Insights, Customer Segments)
  
![drill-through](https://github.com/user-attachments/assets/465b09bc-d67f-4ec7-9633-98c9fa79938c)

![E-commerceproject-MadewithClipchamp-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/d09837b0-40e5-4b66-bc61-527051db7f39)

- Added **interactive slicers and filters** for tailored views
- Ensured each page aligned with the **manager’s decision-making needs**

---

### 6️⃣ Final QA & Production

Before finalizing the project:

- Standardized **naming conventions** across tables, columns, and visuals
- Verified all measures and visuals were accurate, intuitive, and met business requirements
- Aligned dashboard storytelling with the core objectives
- Conducted UI polish: layered visuals properly, aligned objects, and ensured responsive design

---

## 🔍 Key Features

- Interactive KPI tracking dashboard
- Time-series performance analysis (monthly/yearly)
- Customer segmentation by value and demographics
- Region-wise and product-level deep dive
- Dynamic visuals via parameterization

---

## 🚀 Tools Used

- Microsoft Power BI
- Power Query Editor
- DAX (Data Analysis Expressions)

---

## 📣 Target Audience

This dashboard is tailored specifically for **sales managers** who need:
- High-level summaries for quick decision-making
- Deep-dives into specific regions, customers, or product categories
- Minimal technical jargon — maximum business insight

---

## 📫 Contact

For feedback, collaboration, or inquiries:  
**Abdurhman Hesham Al Wardany**  
📧 [abdurhmanheshaam@example.com]  
🌐 [https://www.linkedin.com/in/abdurhman-hisham/]

---

## 🎥 Dashboard Walkthrough (Visual Tour)

> Below is a quick tour of the dashboard’s layout, interactivity, and insights.

### 🧩 Report Navigation

![The main Dashboard](https://github.com/user-attachments/assets/9f9ce427-7634-419b-9a4a-e64eee5547d2)


- Multi-page layout tailored to sales managers
- Tabs for KPIs, Region Analysis, Product Insights, and Customers

---

### 📊 High-Level KPI Summary

![The main Dashboard](https://github.com/user-attachments/assets/caf646ec-0cac-42bb-bc71-4ff3e5ef658b)


- Tracks total revenue, profit, units sold, and customer count
- Dynamic time filters and year-over-year comparisons

---

### 🌍 Regional Performance Analysis

![Map](https://github.com/user-attachments/assets/35699987-1f1d-4dbe-a8b3-c44c6c8dfd9c)


- Side-by-side performance of regions
- Drill-through support for cities and sales reps

---

### 📦 Product Insights

![Product](https://github.com/user-attachments/assets/5ad4ca8e-4ac6-47c1-b9a1-4e8c049bf179)


- Top-selling products
- Trends over months and seasons
- Profit contribution and stock status

---

### 👤 Customer Segmentation

![Product](https://github.com/user-attachments/assets/95413d74-1946-4dca-a587-1849f29b28d3)


- Highlights VIP customers based on frequency and value
- Age and demographic filters
- Dynamic customer ranking

---

## 📸 Note:
All visuals above are screenshots from the actual Power BI dashboard.



