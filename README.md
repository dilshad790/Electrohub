# ElectroHub: Omni-Channel Retail Sales & Inventory Intelligence

## 📌 Project Overview
**ElectroHub** is a data-driven intelligence project designed for a diverse retail store managing categories ranging from **Electronics and Footwear to Home Appliances and Personal Care**. The goal of this dashboard is to provide stakeholders with a 360-degree view of sales performance, profitability, and inventory health to optimize supply chain decisions and marketing strategies.

### 🎯 Business Objectives
Based on the project requirements, the dashboard answers the following critical business questions:
1.  **Performance Benchmarking:** Identification of the Top 5 and Bottom 5 products based on Sales, Profit, and Quantity Sold.
2.  **Temporal Analysis:** Visualizing how sales trends fluctuate across daily, monthly, quarterly, and annual timeframes.
3.  **Profitability Correlation:** Examining the relationship between Sales and Profit to identify high-margin vs. high-volume drivers.
4.  **Geographic Distribution:** Mapping sales performance across various cities to pinpoint market penetration.
5.  **Promotion Impact:** Analyzing the average discount offered per category and its effect on total order volume.

---

## 🛠️ Technical Stack
* **Data Visualization:** Power BI Desktop
* **Data Transformation:** Power Query (M Language)
* **Analytical Logic:** DAX (Data Analysis Expressions) for calculated measures
* **Data Source:** Multi-category transactional dataset (Electronics, Footwear, Clothing, etc.)

---

## 📊 Dashboard Insights & Visuals

### 1. Product Performance Analysis
This view focuses on extreme values, allowing managers to see which products are over-performing and which require stock clearance or marketing intervention.

![Top and Bottom Product Performance Analysis](Screenshot%202026-05-07%20214031.png)

* **Insight:** The **Apple iPhone** dominates both total sales and profit, while low-ticket items like **Colgate** represent the bottom tier of revenue generation.

### 2. Market Geography & Profitability Correlation
By utilizing scatter plots and map visuals, we can identify which regions are profitable and if sales volume consistently leads to profit.

![Sales vs Profit and Geographic Distribution](Screenshot%202026-05-07%20214102.jpg)

* **Key KPI:** Successfully tracked **3,510 total orders** with a clear concentration of revenue in major urban hubs like Delhi and Mumbai.
* **Discount Strategy:** High-value items like the **Apple MacBook** and **Sony Bravia** carry the highest average discounts to drive competitive edge.

### 3. Sales Trend Intelligence
A line-chart analysis showing the "heartbeat" of the business throughout the fiscal year.

![Sales Trends by Month](Screenshot%202026-05-07%20214041.png)

* **Observation:** Significant sales peaks are observed in **October and November**, likely correlating with seasonal festive demand.

### 4. Dynamic Filtering & Transaction Drill-Down
To ensure the report is truly interactive, advanced slicing features were implemented to allow users to filter by specific customers, product names, or promotion IDs.

![Interactive Filter Features](Screenshot%202026-05-07%20214129.png)

* **Granularity:** The "Filter Features" page allows for a deep dive into individual transaction IDs, showing the exact discount percentage and net sales per line item.

---

## 🚀 Key Takeaways & Impact
* **Inventory Optimization:** By identifying the "Bottom 5" products by unit sold, the business can reduce storage costs for slow-moving inventory.
* **Strategic Discounting:** The correlation between "Average Discount" and "Net Sales" helps in fine-tuning promotional campaigns for underperforming categories.
* **Regional Growth:** Geographic insights suggest potential for expansion in regions with high order counts but lower total revenue.

---

## 📂 Project Structure
* `ElectroHub_Dashboard.pbix`: The core Power BI file.
* `Data/`: Folder containing raw CSV/Excel datasets.
* `Documentation/`: Detailed project notes and requirement sheets.

---

### How to use this repository:
1. Download the `.pbix` file.
2. Open in **Power BI Desktop**.
3. Use the **Navigation Pane** on the left to toggle between Analysis, Trends, and Filter features.
