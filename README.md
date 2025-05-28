 Excel Sales Dashboard – Profit, Sales & Customer Insights
This project is a comprehensive Excel dashboard that provides key business insights using pivot tables and pivot charts. It explores data from multiple angles like branch performance, product category sales, customer satisfaction, payment preferences, and monthly profit trends.

📁 Dataset Columns Used
invoice_id

Branch

City

category

unit_price

quantity

Month

Date

payment_method

rating

profit_margin

Total Sales

Profit

📌 Charts Included
1. 🏢 Total Profit by Branch (Pie Chart)
Pivot Settings:

Rows: Branch

Values: Sum of Profit

Purpose: Shows which branch generates the most profit. A pie chart makes it easy to compare branch contributions visually.

2. 📦 Total Sales and Quantity by Category (Column Chart)
Pivot Settings:

Rows: category

Values: Sum of Total Sales, Sum of quantity

Purpose: Compares revenue and quantity sold across different product categories.

3. 🌆 Average Rating and Total Profit by City (Combo Chart)
Pivot Settings:

Rows: City

Values: Average of rating, Sum of Profit

Purpose: Combines customer satisfaction and profit metrics to evaluate city-wise performance.

4. 💳 Profit and Quantity by Payment Method (Column Chart)
Pivot Settings:

Rows: payment_method

Values: Sum of Profit, Sum of quantity

Purpose: Analyzes profitability and volume by payment method.

5. 📈 Monthly Profit Trend (Line Chart)
Pivot Settings:

Rows: Month (created from Date)

Values: Sum of Profit

Purpose: Displays profit trends over time to observe seasonal or monthly patterns.

6. 🧾 Transaction Distribution by Payment Method (Pie Chart)
Pivot Settings:

Rows: payment_method

Values: Count of invoice_id

Purpose: Shows what percentage of transactions use each payment method.

🧮 Tools & Techniques Used
Microsoft Excel

Pivot Tables

Pivot Charts (Pie, Column, Line, Combo)

Calculated Columns (e.g., unit_price * quantity for Total Sales)

Data cleaning and formatting

📈 Use Case
This dashboard is ideal for small businesses or analysts looking to gain quick, actionable insights into sales trends, profitability, and customer behavior using just Excel—no code or external tools needed.

