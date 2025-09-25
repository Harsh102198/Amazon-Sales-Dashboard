# Amazon-Sales-Dashboard

This Power BI dashboard provides a clear overview of sales performance, order quantities, and total orders, along with product and channel insights.

🗂 Data Source

The dataset contains the following columns:

Order ID, Date, Status, Fulfilment, Sales Channel, ship-service-level, Style, SKU, Category, Size, ASIN, Courier Status, Qty, currency, Amount, Ship_City, Ship _State, ship-postal-code, Ship_Country, B2B, Fulfilled-By, Total_Sales.

Data cleaned to ensure Date and numeric fields are correct.

📌 Dashboard Components
1️⃣ KPI Cards

Quick overview of key metrics:

💰 Total Sales → Sum of Amount

📦 Total Quantity → Sum of Qty

📝 Total Orders → Count of Order ID


2️⃣ Charts
a) Column Chart

Purpose: Compare sales or quantity across categories/cities

X-axis: Category / Ship_City

Y-axis: Sum of Amount / Qty


b) Donut Chart

Purpose: Show distribution of sales by channel

Legend: Sales Channel

Values: Sum of Amount


c) Line Chart

Purpose: Show sales trend over time

X-axis: Date

Y-axis: Sum of Amount
