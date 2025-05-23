# Power BI Project – Telecom Sales Report (AdventureWorks 2019)
**Work Sample by Erfan Mirzakhani**

This interactive Power BI report is built using the AdventureWorks 2019 dataset and simulates sales performance reporting for a **telecom business scenario**. It demonstrates skills in data modeling, DAX, UX design, slicer logic, bookmarks, drilldowns, conditional formatting, and mobile view customization.

---

## ⚙️ Features Overview

### ✅ **Row-Level Security (RLS)**
- Configured and tested for access based on country region roles.

### ✅ **Mobile View**
- Optimized layout for mobile display.
- Horizontal, repositioned navigation menu on top (manually redesigned for responsiveness).

### ✅ **Custom Navigation**
- Bookmark-based sidebar menu on every page.
- Reset filter buttons using bookmarks and slicer groups.

---

## 📊 Pages & Visuals

### **1. Sales Overview**
- **Visuals:**
  - Line Chart – Total Sales Trend
  - Treemap – Total Sales by Country Region
  - 3 KPI Cards – (Total Sales, Last Year Sales, and YoY Growth %)
- **Slicers:**
  - Product Category
  - Year
- **Features:**
  - Dynamic chart Title
  - Clean mobile version
  - Tooltip Page (on Treemap hover)

---

### **2. Region**
- **Visuals:**
  - Matrix – Region > City (Total Sales)
  - Bar Chart – Total Sales by Region Country Names
  - Line Chart – Total Sales Trend divided by Country Region
  - 3 KPI Cards - (Total Sales, Top Region Sales, and YoY Growth %)
- **Slicers:**
  - Product Category
  - Year
  - Country Region
- **Features:**
  - Reset Filters Button
  - Dynamic Page Title

---

### **3. Product**
- **Visuals:**
  - Bar Chart – Total Sales by Product Category with drilldown to Subcategory > Product Names
    - Conditional Formatting applied based on relative sales performance (within hierarchy level).
  - Matrix – Product Category > Subcategory > Product Name (Total Sales)
- **Slicers:**
  - Product Category
  - Year
  - Country Region
- **Features:**
  - Reset Filters Button
  - Dynamic Page Title

---

## 🛠️ Technical Details

- **Data Source:** AdventureWorksDW2019 (sample data modified for telecom-like scenario)
- **Data Modeling:** Star schema, relationships between Dim and Fact tables
- **DAX Techniques Used:**
  - Conditional formatting logic with drilldown hierarchy detection
  - Dynamic titles
  - RLS roles
  - Measure-driven slicer behavior
- **Mobile Layout:** Customized visuals, font sizing, and mobile-responsive navigation

---

## 📁 Files Included
- `TelecomSalesReport.pbix`
- `README.md`

---

## 🧠 Author
**Erfan Mirzakhani**  
Business Data Analyst | Data-Driven Decision Making | BI & Data Analytics 
LinkedIn: https://www.linkedin.com/in/erfanmirzakhani
GitHub: [Wandering-Sci](https://github.com/Wandering-Sci)  
