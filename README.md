# 🛒 Grocelytics — Blinkit Sales & Operations Dashboard (Power BI + SQL)

A complete **Business Intelligence (BI)** project that analyzes sales, performance, and outlet operations for a **Blinkit-style grocery business** using **Power BI**, **SQL**, and **Excel**.

This repository demonstrates how data can be transformed into insights through data cleaning, SQL analysis, DAX measures, and Power BI visualization.

---

## 🚀 Project Overview

**Grocelytics** answers key business questions like:
- Which **outlet type or size** generates the most revenue?
- What **item types** perform best or worst?
- How do **fat content** and **outlet location tier** affect sales?
- Are there observable **yearly trends** in sales and ratings?
- How can managers use data to make **data-driven decisions**?

This project demonstrates the **end-to-end BI workflow**:  
> Raw Data → SQL Analysis → Data Modeling → Power BI Dashboard → Business Insights

## 📊 Dashboard Features

| Feature | Description |
|----------|--------------|
| 🧾 **KPI Overview** | Total Sales, Average Sales, Items Count, and Average Rating |
| 📈 **Sales Analysis** | Visualizes sales by Item Type, Fat Content, Outlet Type, and Tier |
| 🏬 **Outlet Insights** | Compares performance across outlet sizes and locations |
| 📆 **Yearly Trends** | Displays growth patterns and performance over time |
| ⭐ **Customer Insights** | Highlights average ratings and satisfaction indicators |

---

## 🧠 Key Insights

- **Medium-sized outlets** generate the highest total sales.  
- **Regular-fat products** sell more than low-fat products.  
- **Tier 3 locations** record better overall sales volumes.  
- **Supermarket Type 1** outlets are top performers.  
- Year-over-year analysis shows **consistent growth** in both sales and ratings.

---

## ⚙️ Tools & Technologies Used

| Category | Tool |
|-----------|------|
| Data Source | Excel Dataset (`BlinkIT Grocery Data.xlsx`) |
| Data Analysis | SQL Server / MySQL |
| Data Visualization | Power BI Desktop |
| Data Modeling | Power Query, DAX |
| Documentation | Markdown, Excel Notes |

---

## 💻 How to Use
Step 1: Clone or Download the Repository
    
      git clone https://github.com/MuvvaThirapathaswami/BlinkIt_Grocelytics.git

Step 2: Open in Power BI

    Launch Power BI Desktop.
    Open Blinkit.pbix.
    If the Excel path has changed, relink BlinkIT Grocery Data.xlsx.

Click Refresh to load and visualize the data.

 Step 3: Run SQL Queries (Optional)

    Navigate to SQL Data and Doc (Use for SQL Analysis).
    Open and run SQL queries in SQL Server Management Studio or another SQL client.
    
Use the scripts to validate data and compute KPIs.

**Data Model Overview**

Fact Table: Contains transaction-level sales data (Sales, Quantity, Rating)

Dimension Tables:

Item Table: Item Type, Fat Content, Category

Outlet Table: Size, Type, Location Tier, Year Established

**🧮 DAX Measures (Used in Power BI)**

    Total Sales = SUM('Sales'[SalesAmount])

    Average Sales = 
    DIVIDE([Total Sales], DISTINCTCOUNT('Sales'[InvoiceID]))

    Item Count = COUNTROWS('Sales')

    Average Rating = AVERAGE('Sales'[Rating])

📈 Dashboard Pages

1.Overview Dashboard — Displays KPIs and sales summary

2.Item Insights — Item performance based on type and fat content

3.Outlet Insights — Comparison of size, type, and tier

4.Trends Dashboard — Year-over-year and category trends

🧩 Business Benefits

>>Empowers decision-makers with data-backed insights

>>Enables comparative analysis across outlets and categories

>>Improves inventory and marketing planning

>>Enhances customer experience tracking through ratings

📜 License

This project is released under the MIT License.
You are free to use, modify, and distribute for learning or portfolio purposes.

👩‍💻 Author : **Muvva Thirapathaswami**

📍 Data & BI Enthusiast

💬 Feedback: If you found this project helpful:

⭐ Star the repository

🍴 Fork it to build your own version

💬 Share feedback or issues in the Issues tab

**“Grocelytics turns raw grocery data into powerful business insights.”**


---

### ✅ Key Features of This Version:
- No video references (fully standalone GitHub project).
- Clean, readable formatting with emoji headers (for professional + engaging style).
- Explains setup, features, insights, DAX, and tools clearly.
- Recruiter-friendly and perfect for portfolios or Power BI showcases.


