# 📊 Excel Sales Dashboard – Profit, Sales & Customer Insights

This project is a comprehensive Excel dashboard that provides key business insights using PivotTables and PivotCharts. It analyzes sales performance, profit, and customer behavior across various business dimensions.

---

## 📁 Dataset Columns

- `invoice_id`  
- `Branch`  
- `City`  
- `category`  
- `unit_price`  
- `quantity`  
- `Month`  
- `Date`  
- `payment_method`  
- `rating`  
- `profit_margin`  
- `Total Sales`  
- `Profit`

---

## 📌 Pivot Charts Overview

### 1. 🏢 Total Profit by Branch *(Pie Chart)*
- **Pivot Table:**
  - Rows: `Branch`
  - Values: Sum of `Profit`
- **Purpose:** Visualizes which branch contributes most to the overall profit.

---

### 2. 📦 Total Sales and Quantity by Category *(Column Chart)*
- **Pivot Table:**
  - Rows: `category`
  - Values: Sum of `Total Sales`, Sum of `quantity`
- **Purpose:** Compares sales revenue and quantity sold by product category.

---

### 3. 🌆 Average Rating and Total Profit by City *(Combo Chart)*
- **Pivot Table:**
  - Rows: `City`
  - Values: Average of `rating`, Sum of `Profit`
- **Purpose:** Analyzes the relationship between customer satisfaction and profit across cities.

---

### 4. 💳 Profit and Quantity by Payment Method *(Column Chart)*
- **Pivot Table:**
  - Rows: `payment_method`
  - Values: Sum of `Profit`, Sum of `quantity`
- **Purpose:** Evaluates sales and profitability by payment type.

---

### 5. 📈 Monthly Profit Trend *(Line Chart)*
- **Pivot Table:**
  - Rows: `Month` (derived from `Date`)
  - Values: Sum of `Profit`
- **Purpose:** Tracks how profit changes month-by-month.

---

### 6. 🧾 Transaction Count by Payment Method *(Pie Chart)*
- **Pivot Table:**
  - Rows: `payment_method`
  - Values: Count of `invoice_id`
- **Purpose:** Shows the distribution of transactions across different payment methods.

---

## 🧰 Tools Used

- Microsoft Excel  
- PivotTables  
- PivotCharts (Pie, Column, Line, Combo)  
- Basic formulas (e.g., `unit_price * quantity`)  
- Data formatting and calculated fields

---

## ✅ Use Case

This dashboard is ideal for small businesses and analysts who want to:

- Monitor branch-wise profitability  
- Analyze product sales performance  
- Understand customer satisfaction by location  
- Evaluate trends in profit and payment behavior  
- All using just Microsoft Excel – no coding required.

---

## 📎 Sample Screenshot

![image](https://github.com/user-attachments/assets/e40cb1a0-7109-4ce1-aa63-50805e862571)


---

## 📂 File Structure

- `Sales_Dashboard.xlsx` – Contains raw data, PivotTables, and charts
- `README.md` – Project overview and documentation

---

## 📬 Contact

For feedback or questions, feel free to reach out!

