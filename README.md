Pizza Sales Power BI Dashboard

Overview

This project presents an interactive Pizza Sales Dashboard created using Power BI, with data imported from MS SQL Server. It provides a detailed analysis of sales performance, customer ordering trends, and product insights for a pizza company.

The goal was to analyze trends across various time periods and categories using SQL for data extraction and DAX for calculations and KPIs.

Data & Visualization Tools

- Power BI – Data visualization and dashboard development
- SQL Server – Backend data storage and query execution
- DAX (Data Analysis Expressions) – For calculated fields, KPIs, and measures
- Microsoft Excel – For preprocessing and formatting documentation

 🔹Dashboard Screenshots

🔹 Home Page
Highlights:
- Total Revenue, Orders, and Pizzas Sold
- Daily & Monthly Order Trends
- Sales by Category and Pizza Size


🔹Best & Worst Sellers Page
Highlights:
- Top/Bottom 5 Pizzas by Revenue, Quantity, and Orders
- Best performing pizza types
- Underperforming SKUs identified for business action

🔹 Key DAX Measures

- Total Revenue = SUM(pizza_sales[total_price])
- Total Orders = DISTINCTCOUNT(pizza_sales[order_id]
- Avg Order Value = [Total Revenue] / [Total Orders]
- Avg Pizzas Per Order = [Total Pizzas Sold] / [Total Orders]

🔹 Full SQL queries can be found in the Word file.

🔹 Key Insights

- Busiest Days: Friday & Saturday evenings
- Top Performing Category: Classic pizzas
- Highest Sales Volume: Large-sized pizzas
- Least Popular: Brie Carre pizza underperformed across all metrics


 ✅ Project Status

✔️ Completed  
📁 Open to enhancement (e.g., slicer-based filtering by store or city)


🔹Let's Connect

If you liked this project or have feedback, feel free to connect:

- 📧 bhaizeeshan710@gmail.com
- 💻 https://github.com/zeeshan3020




