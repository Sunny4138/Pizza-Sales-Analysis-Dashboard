Pizza Sales Analysis-Dashboard


The Pizza Sales Dashboard provides a comprehensive analytical overview of pizza retail performance using SQL, Excel, and Power BI.

It enables business users to:

Monitor key sales KPIs (revenue, orders, product performance)

Identify top and bottom-performing pizzas

Analyze sales trends by date, category, and size

Support inventory optimization and marketing decisions through data-driven insights

By visualizing a full year of sales data, the dashboard empowers decision-makers to recognize profitable trends, improve low-performing products, and maximize business growth.

⚙️ Steps Followed

Step 1: Loaded pizza sales data (CSV dataset) into Power BI Desktop.

Step 2: Cleaned and validated data using Power Query — verified column distribution, data quality, and profiles.

Step 3: Handled missing or inconsistent values in quantity, price, and category columns.

Step 4: Created calculated columns and DAX measures for key KPIs:

Total Revenue

Average Order Value (AOV)

Total Pizzas Sold

Total Orders

Average Pizzas per Order

Step 5: Designed daily and monthly trend visuals to highlight peak sales periods.

Step 6: Built bar and donut charts for sales by category and size.

Step 7: Added visuals for Top 5 and Bottom 5 pizzas based on revenue, quantity, and order count.

Step 8: Integrated interactive slicers for filtering by category, size, and time period.

Step 9: Applied custom themes, legends, and tooltips for a polished and intuitive interface.

Step 10: Published the report to Power BI Service for sharing and collaboration.

📈 Key Insights
🔹 Revenue & Order Volume

Total Revenue: ₹817.86K

Total Orders: 21,350

Total Pizzas Sold: 49,574

Average Order Value: ₹38.31

Average Pizzas per Order: 2.32

🔹 Peak Sales Periods

Maximum sales observed during weekends (Friday & Saturday).

July and January recorded the highest order volumes across the year.

🔹 Sales by Category & Size

Classic pizzas lead in both sales volume and revenue share.

Large-sized pizzas are the most popular and profitable.

🔹 Product Performance

Dashboard highlights Top 5 best-selling and Bottom 5 least-performing pizzas.

Insights guide menu optimization and targeted promotions.

🔹 Sales Distribution

Interactive visuals enable deep-dive analysis by pizza category, size, and time.

🧾 Dataset Details
Attribute	Description
File Name	pizza_sales.csv
Columns	order_id, order_date, pizza_name, pizza_category, pizza_size, quantity, total_price
Duration	Full year (Jan–Dec 2015 or equivalent dataset)
Source	Pizza retail transactional dataset for analytics and reporting
 SQL & DAX Highlights

Examples of SQL queries and DAX expressions used for KPIs and trend analysis are included in the file:

PIZZA-SALES-SQL-QUERIES.docx

Sample SQL Query – Total Revenue
SELECT SUM(total_price) AS TotalRevenue
FROM pizza_sales;


Additional queries include calculations for:

Average Order Value

Order Count & Quantity

Monthly & Daily Sales Trends

Category and Size Breakdown

Top/Bottom Sellers

DAX Measures in Power BI were also created for:

KPI cards

Dynamic filtering

Trend visualization

 Usage & Deployment

Clone or download the repository.

Load the provided dataset (pizza_sales.csv) into your preferred SQL or Power BI environment.

Use the provided SQL scripts for data preparation and KPI computation.

Open the Power BI file and refresh data connections.

Interact with slicers and visuals to explore custom insights.

 Tools & Technologies

SQL → Data processing & KPI computation

Excel → Data validation & pivot exploration

Power BI → Interactive visualization & reporting

DAX → Custom measures and calculated fields

 


 Conclusion

This dashboard provides a holistic view of pizza sales performance, combining SQL-driven insights with Power BI visual analytics.
It empowers stakeholders to make data-informed decisions about:

1.Product performance

2.Marketing strategy

3.Seasonal sales planning

4.Inventory optimization
