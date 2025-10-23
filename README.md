# 🍕 Pizza Sales Analysis Dashboard

## (1).Overview
The **Pizza Sales Dashboard** provides a **comprehensive analytical overview** of pizza retail performance using **SQL**, **Excel**, and **Power BI**.

It helps business users to:
- **Monitor key sales KPIs** such as revenue, orders, and product performance.  
- **Identify top and bottom-performing pizzas.**  
- **Analyze sales trends** by date, category, and size.  
- **Optimize inventory and marketing** decisions through data-driven insights.  

By visualizing a **full year of sales data**, the dashboard empowers decision-makers to recognize **profitable trends**, improve **low-performing products**, and **maximize business growth**.

---

## (2).Steps Followed

1. **Loaded pizza sales data** (CSV dataset) into **Power BI Desktop**.  
2. **Cleaned and validated data** using **Power Query** — verified column distribution, data quality, and profiles.  
3. **Handled missing or inconsistent values** in quantity, price, and category columns.  
4. **Created calculated columns and DAX measures** for key KPIs:
   - Total Revenue  
   - Average Order Value (AOV)  
   - Total Pizzas Sold  
   - Total Orders  
   - Average Pizzas per Order  
5. **Designed daily and monthly trend visuals** to highlight peak sales periods.  
6. **Built bar and donut charts** for sales by category and size.  
7. **Added visuals** for Top 5 and Bottom 5 pizzas based on revenue, quantity, and order count.  
8. **Integrated interactive slicers** for filtering by category, size, and time period.  
9. **Applied custom themes, legends, and tooltips** for a polished, professional interface.  
10. **Published the report to Power BI Service** for sharing and collaboration.  

---

## (3).Key Insights

### 🔹 Revenue & Order Volume
- **Total Revenue:** ₹817.86K  
- **Total Orders:** 21,350  
- **Total Pizzas Sold:** 49,574  
- **Average Order Value:** ₹38.31  
- **Average Pizzas per Order:** 2.32  

### 🔹 Peak Sales Periods
- Maximum sales observed during **weekends (Friday & Saturday)**.  
- **July and January** recorded the highest order volumes of the year.  

### 🔹 Sales by Category & Size
- **Classic pizzas** dominate both sales volume and revenue.  
- **Large-sized pizzas** are the most popular and profitable.  

### 🔹 Product Performance
- Highlights **Top 5 best-selling** and **Bottom 5 least-performing** pizzas.  
- Insights guide **menu optimization** and **targeted promotions**.  

### 🔹 Sales Distribution
- Interactive visuals enable **in-depth analysis** by **category, size, and time**.  

---

## (4).Dataset Details

| **Attribute** | **Description** |
|----------------|-----------------|
| **File Name** | `pizza_sales.csv` |
| **Columns** | order_id, order_date, pizza_name, pizza_category, pizza_size, quantity, total_price |
| **Duration** | Full year (Jan–Dec 2015 or equivalent dataset) |
| **Source** | Pizza retail transactional dataset for analytics and reporting |

---

## (5).SQL & DAX Highlights

Examples of **SQL queries** and **DAX measures** used for KPI calculations and trend analysis are included in:  
 **`PIZZA-SALES-SQL-QUERIES.docx`**
### Sample SQL Query – Total Revenue

SELECT SUM(total_price) AS TotalRevenue
FROM pizza_sales;


Conclusion

The Pizza Sales Dashboard delivers a comprehensive, data-driven overview of pizza retail performance by integrating SQL, Excel, and Power BI for end-to-end analysis.
It transforms raw transactional data into meaningful business insights, enabling organizations to monitor KPIs, identify trends, and make informed decisions.

Through this project, businesses can:

Identify top-performing products and address underperforming ones.

Optimize marketing and promotions based on seasonal and category-wise demand.

Enhance inventory management using insights from sales patterns.

Boost profitability and efficiency through continuous performance monitoring.

In conclusion, this dashboard acts as a powerful business intelligence tool, empowering stakeholders to make strategic, data-backed decisions and drive sustainable business growth.
















