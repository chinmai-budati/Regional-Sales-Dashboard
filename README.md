### **Power BI Sales Performance & Regional Analytics**

**1. Sales & Profit Performance Analytics:**
A high-impact Power BI dashboard designed to provide a 360-degree view of retail performance, focusing on regional growth, product demand, and Year-over-Year (YoY) profitability across diverse market segments.

**2. Purpose:**
The purpose of this dashboard is to empower executive leadership and regional managers with actionable insights into company health. By tracking KPIs like Total Sales, Profit Margins, and Order Quantities, stakeholders can identify underperforming regions, optimize inventory distribution, and evaluate the success of sales strategies compared to the previous year's benchmarks.

**3. Tech Stack:**

* **📊 Power BI Desktop** – Used for complex data modeling and building a star schema architecture.
* **📂 Power Query (ETL)** – Utilized for cleaning e-commerce datasets, handling date formats, and merging regional tables.
* **🧠 DAX (Data Analysis Expressions)** – Implementation of advanced Time Intelligence (PY, YoY Growth) and Field Parameters for dynamic metric switching.
* **🎨 UI/UX Design** – Integration of custom background layouts and synchronized color palettes for a professional "dark mode" executive aesthetic.

**4. Data Source:**
The project utilizes a comprehensive Retail Sales Dataset containing:

* **Order Details:** Order Date, Ship Date, and Ship Mode.
* **Product Hierarchy:** Category, Sub-Category, and Product Name.
* **Customer Geography:** Region (Central, East, South, West), State, and City.
* **Financial Metrics:** Sales, Profit, Quantity, and Discount rates.

**5. Features:**

**Business Problem**
Leadership often struggles to see "the big picture" across multiple regions without getting lost in raw spreadsheets. It is difficult to quickly identify if a dip in profit is due to a specific region or a broader year-over-year decline in a product category.
Stakeholders need to answer:

* Which regions are exceeding their previous year's sales targets?
* What is the correlation between product categories and overall profitability?
* How do seasonal trends impact quantity sold across different states?

**Goal of the Dashboard**
To provide a performance-centric view of the retail portfolio that enables:

* **Dynamic Metric Selection:** A single slicer allows users to toggle the entire dashboard between "Sales," "Profit," and "Quantity."
* **Trend Monitoring:** Comparison of Current Year (CY) vs. Previous Year (PY) to measure real-time growth.
* **Geographic Deep-Dives:** Using spatial data to visualize market penetration and regional contributions.

**Walkthrough of Key Visuals:**

* **KPI Overview (Top Ribbon):** Four dedicated regional cards (Central, East, South, West) showing the selected metric, its PY comparison, and a YoY growth percentage.
* **Regional Sparklines:** Monthly trend lines located within KPI cards to provide a quick "heartbeat" of regional performance over time.
* **Interactive Bubble Map:** A geographic visualization where bubble size represents the intensity of the selected metric across the United States.
* **Sales/Profit by Category (Bar Charts):** A breakdown of performance by product category to identify top revenue drivers.
* **YoY Comparison Grid:** A detailed matrix at the bottom providing a granular look at monthly performance with conditional formatting indicators (Red/Green) for growth.

**Business Impact & Insights**

* **Strategic Growth:** Identifying that the "West" region has the highest YoY profit growth can lead to increased marketing budget allocation in that territory.
* **Inventory Optimization:** Tracking quantity trends helps supply chain teams anticipate high-demand months.
* **Profitability Refinement:** Pinpointing categories with high sales but low profit allows for a more focused review of discount structures and shipping costs.

**6. Screenshot:**
