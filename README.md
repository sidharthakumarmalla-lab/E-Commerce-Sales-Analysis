# E-Commerce-Sales-Analysis
This project performs exploratory data analysis (EDA) on an e-commerce dataset to uncover key business insights such as sales trends, top-performing months, cities with the highest orders, and best-selling products.

# 🚀 Project Overview

The goal of this project is to analyze sales data and answer important business questions:

* Which month had the highest sales?
* Which city placed the most orders?
* What products are sold the most and why?
* How do price and quantity influence sales?

# 📁 Dataset

The dataset used in this project is stored in .feather format:

* **Sales_data.ftr**

It contains transactional data including:
* Order ID
* Product
* Quantity Ordered
* Price Each
* Order Date
* Purchase Address
* Sales

# 🛠️ Technologies Used
* Python 🐍
* Pandas
* NumPy
* Matplotlib

# 🔍 Data Preprocessing

Key steps performed:

* Removed missing values
* Converted columns to appropriate data types
* Cleaned invalid numeric entries
* Extracted useful features such as:
* Month from Order Date
* City from Purchase Address

# 📈 Analysis & Insights
## 1. 📅 Best Month for Sales
* Extracted month from order date
* Aggregated total sales per month
* Visualized using a bar chart

**Insight**: Identified the month with the highest revenue.

## 2. 🏙️ City with Maximum Orders
* Extracted city names from address
* Counted total orders per city
* Calculated percentage contribution
* Visualized using a pie chart

**Insight**: Determined which city contributes the most to total orders.

## 3. 📦 Most Sold Products
* Aggregated:
    * Total quantity sold
    * Average price per product
* Sorted products by quantity sold
* Visualized relationship between quantity and price

**Insight**: Identified top-selling products and analyzed why they perform well.

# 📊 Visualizations

The project includes:

* Bar charts for monthly sales
* Pie charts for city-wise distribution
* Combined plots for product analysis

# 📈 Key Insights

* 💡 High sales concentration in specific months
* 💡 Few cities dominate total orders
* 💡 Lower-priced items sell more frequently
* 💡 Demand influenced by product affordability

# 📌 Conclusion

* This analysis demonstrates how data-driven insights can significantly improve decision-making in an e-commerce environment. By examining sales trends, geographic distribution, and product performance, the project highlights clear patterns in customer behavior and business performance.

* The findings reveal that sales are not evenly distributed across time or location—certain months and cities contribute disproportionately to overall revenue. Additionally, product analysis shows that pricing plays a crucial role in demand, with more affordable items generally achieving higher sales volumes.

* Overall, this project reinforces the importance of exploratory data analysis (EDA) as a foundational step in understanding business dynamics. The insights derived can support strategic decisions such as inventory planning, targeted marketing, and pricing optimization.

* With further enhancements like predictive modeling and customer segmentation, this analysis can evolve into a powerful decision-support system for e-commerce businesses.












