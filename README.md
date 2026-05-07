# ElectroHub: Omni-Channel Retail Sales & Inventory Intelligence

## 📌 Project Overview
**ElectroHub** is a data-driven intelligence project designed for a diverse retail store managing categories ranging from **Electronics and Footwear to Home Appliances and Personal Care**. This dashboard provides a 360-degree view of sales performance, profitability, and inventory health to optimize supply chain decisions and marketing strategies.

### 📋 Product Categories Covered:
- 💻 Electronics & Accessories
- 👟 Footwear
- 👕 Clothing
- 🏠 Home Appliances
- 🍳 Kitchenware
- 💼 Bags
- 🧴 Personal Care

---

## 🛠️ Technical Stack
* **Data Visualization:** Power BI Desktop
* **Data Transformation:** Power Query (M Language)
* **Analytical Logic:** DAX (Data Analysis Expressions)
* **Data Source:** Multi-category transactional dataset

---

## 📊 Dashboard Insights & Visuals

### 1. High-Level KPI Summary
The "Slider for sales" page provides an immediate snapshot of the business's health using summarized metrics.
![Sales KPIs and Sliders](Screenshots/Screenshot%202026-05-07%20214114.png)
* **Total Sales:** 110M
* **Total Units Sold:** 6.1K
* **Total Orders:** 3,510 (as shown on the City Analysis page)

### 2. Time-Period Comparison & Filtering
One of the core features is the ability to compare performance between two distinct periods using the **Date Slider**.
![Interactive Filter Features](Screenshots/Screenshot%202026-05-07%20214129.png)
* **Dynamic Range:** Users can select any two dates to compare Sales, Profit, and Quantity Sold.
* **Granular Drill-Down:** The "Filter Features" page provides a row-level transaction table including:
    - CustomerID, Product ID, and PromotionID
    - Discount Percentage & Value
    - Net Sales vs. Total Sales (calculating the impact of discounts)

### 3. Product Performance Analysis (Top/Bottom 5)
Focuses on identifying extreme performers to assist in procurement and clearance strategies.
![Top and Bottom Performance](Screenshots/Screenshot%202026-05-07%20214031.png)
* **Insights:** Tracks Top/Bottom 5 by **Sales**, **Profit**, and **Units Sold** simultaneously.

### 4. Sales vs. Profit & Geographic Penetration
A multi-dimensional view of where the money is coming from and if volume equals value.
![City Analysis & Profitability](Screenshots/Screenshot%202026-05-07%20214102.png)
* **Map Visual:** Pinpoints sales in cities like Delhi, Mumbai, Kanpur, and Bangalore.
* **Scatter Plot:** Analyzes the relationship between Net Sales and Profit to find high-margin outliers.
* **Category Discounts:** A bar chart displaying the **Average Discount** per product to ensure promotions aren't hurting the bottom line.

### 5. Temporal Trend Analysis
Visualizes the "Sales heartbeat" to detect seasonal peaks.
![Sales Trends](Screenshots/Screenshot%202026-05-07%20214041.png)
* **Trendline:** Shows monthly fluctuations, highlighting high-demand months like October/November.

---

## 🚀 Key Business Impact
* **Inventory Control:** Identifying "Bottom 5" items helps reduce capital tied up in slow-moving stock.
* **Discount Efficiency:** Evaluating Average Discount by category prevents over-discounting high-demand electronics.
* **Regional Strategy:** Directing marketing efforts toward cities with high order counts but lower total value.

---

## 📂 Project Structure
* `ElectroHub_Dashboard.pbix`: The core Power BI file.
* `Data/`: Folder containing raw CSV/Excel datasets.
* `screenshots/`: Folder containing all dashboard images.

---

### How to use this repository:
1. Download the `.pbix` file.
2. Open in **Power BI Desktop**.
3. Use the **Navigation Pane** on the left to toggle between different analysis pages.
