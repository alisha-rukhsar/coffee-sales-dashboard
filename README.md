# Coffee Shop Sales Dashboard — Power BI

## Project Overview
This Power BI project analyzes sales performance for a coffee shop chain using transactional data obtained from Kaggle.  
The dashboard provides a detailed breakdown of sales across product categories, store locations, and times of day.  
The objective is to identify which products perform best, when customers buy the most, and which stores contribute the most to total revenue.

## Business Objectives
- Analyze total sales, orders, and quantity sold across different stores and time periods  
- Compare performance by store location to identify high and low-performing outlets  
- Study hourly and weekday trends to determine the most profitable sales periods  
- Identify top-performing product categories and products driving revenue growth  

---

## Key Metrics
- **Total Sales** — Overall revenue generated across all stores  
- **Total Orders** — Number of customer transactions  
- **Total Quantity Sold** — Units sold during the selected period  
- **Average Daily Sales** — Indicates daily store performance  
- **Sales by Category / Store / Hour** — Identifies high-impact products and periods  

---

## Key Insights
- Weekday sales contributed about 74% of total revenue, while weekends accounted for 26% (for the month of May)  
- Coffee was the highest-selling product category, followed by Tea and Bakery items.  
- Barista Espresso, Brewed Chai Tea, and Hot Chocolate were among the top individual products.  
- Morning hours (7 AM–11 AM) generated the highest volume of transactions, probably due to early morning coffee runs by corporate people.  
- The **Astoria** location led overall sales, showing consistent month-on-month growth.  

---

## Tools & Skills Demonstrated
- **SQL** — Data extraction and preliminary transformation  
- **Power BI Desktop** — Dashboard design and visualization  
- **DAX** — Calculated measures for performance tracking (% change vs. last month, totals, averages)  
- **Data Modeling** — Establishing relationships between transaction and product fields  
- **Business Analysis** — Translating data into actionable retail insights  

---

## Dataset Information
- **Source:** Public dataset downloaded from Kaggle  
- **Data Type:** Transaction-level data for multiple store locations  
- **Duration Covered:** One month of sales activity  

| Column | Description |
|---------|-------------|
| transaction_id | Unique identifier for each transaction |
| transaction_date | Date of sale |
| transaction_time | Time of sale |
| transaction_qty | Quantity of items sold |
| store_id | Unique store identifier |
| store_location | Location name of the store |
| product_id | Unique product identifier |
| unit_price | Price per unit sold |
| product_category | Main category (Coffee, Tea, Bakery, etc.) |
| product_type | Product subtype |
| product_detail | Detailed product description |

---

## Learnings
Through this project, I learned to:
- Combine SQL and Power BI for end-to-end business analytics  
- Create intuitive, business-oriented dashboards for retail data  
- Use DAX to automate calculations and enhance insights  
- Present findings clearly through data visualization and storytelling  

---

*Created using SQL and Power BI — turning coffee sales data into strategic insights.*
