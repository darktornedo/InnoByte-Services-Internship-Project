# 📊 Amazon Sales Analysis
**Project done as part of my internship at [InnoByte Services](#)** 

## 📌 Overview
This project analyzes Amazon sales data to uncover trends, top-performing products, States and Citys. The goal is to provide actionable insights for improving sales strategies, inventory, and operations.

## 🗂️ Dataset
- **Columns:** Order ID, Product Category, Size, Sales Channel, Fulfillment, fulfilled by, Customer Type (B2B/B2C), Order Status, Sales Quantity, Revenue, City, State, Order Date  
- **Business Context:** Dataset contains Amazon orders, including product details, fulfillment info, and sales performance across States and Citys.

## ⚙️ Project Workflow
1. **Data Loading**  
   - Imported Python libraries: Pandas, NumPy, Matplotlib, Seaborn  
   - Loaded the dataset into Jupyter Notebook  

3. **Data Cleaning & Preparation**  
   - Handled missing/null values in `amount` and `fulfilled_by` columns  
   - Renamed all column names from uppercase to lowercase for consistency  
   - Filled missing `amount` values (for non-cancelled orders) with average amount  
   - Replaced `amount` and `qty` values with 0 for cancelled orders  
   - Detected and treated outliers in the `amount` column  

4. **Feature Engineering**  
   - Created new time-based columns: `month`, `year`, and `day_name` from the order date  

5. **Exploratory Data Analysis (EDA)**  
   - Performed univariate, bivariate, and time-series analysis  
   - Visualized category-wise sales, size preferences, fulfillment channels, geographic performance, and weekly trends  

6. **Dashboard Creation**  
   - Exported the cleaned dataset to a CSV file  
   - Imported it into Power BI  
   - Designed an interactive Amazon Sales Analysis dashboard showcasing key KPIs and trends  

---

## 📈 Key Insights
- **Product Performance:** T-shirts and Shirts are the most frequently ordered, with T-shirts generating the highest revenue  
- **Size Preference:** Sizes M, L, and XL are most preferred and most profitable  
- **Fulfillment Channel:** Amazon fulfills most orders (mainly B2C); B2B contributes only 0.7%  
- **Order Status:** Amazon-fulfilled orders have higher shipment counts but slightly more cancellations, while merchant-fulfilled orders
 have more delivered orders  
- **Geography:** Bengaluru, Hyderabad, and Mumbai are top cities; Maharashtra and Karnataka are top states  
- **Sales Trends:** Weekday sales are higher than weekends, with fluctuations indicating possible seasonal/operational effects  

---

## ✅ Recommendations
- Prioritize inventory for high-demand products and sizes.  
- Optimize Amazon fulfillment to reduce cancellations.  
- Target promotions in top cities and states.  
- Leverage weekday trends for sales campaigns.  
- Explore strategies to boost B2B sales.

--- 

## 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Jupyter Notebook**  
- **Excel**
- **Power BI** (for interactive dashboard)

---

## Screenshots / Demos
**Show what the dashboard looks like**
![Amazon Sales Dashboard](https://github.com/darktornedo/InnoByte-Services-Internship-Project/blob/main/Amazon_Sales_Analysis.png)
