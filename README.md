# 🌽 Crop and Market Dashboard

A comprehensive data visualization project built using **Power BI**, focusing on sales and quantity analysis for a local farmer's market. The dashboard presents customer behavior, vendor performance, and product-level insights to enable better market understanding and business decisions.

---


## 🔧 Steps Followed

1. **Data Loading**  
   Imported the raw `.csv` dataset into Power BI.

2. **Data Cleaning**  
   - Removed duplicates and null values  
   - Standardized column names  
   - Converted data types appropriately (e.g., dates, numerical fields)

3. **Data Modeling**  
   - Created proper relationships between fact and dimension tables  
   - Defined one-to-many relationships where needed  
   - Implemented a star schema for better query performance

4. **DAX Measures**  
   Used **DAX (Data Analysis Expressions)** to create important measures such as:  
   - `Total Sales`  
   - `Total Quantity Sold`  
   - `Unique Customers`  
   - `Product-wise Sales and Quantity`  
   - `Vendor-wise Aggregation`  
   - `Customer ZIP vs Quantity Analysis`

5. **Dashboard Development**  
   Designed two dashboards:
   - **Sales Dashboard**
   - **Quantity Dashboard**

   These visualizations were created using:
   - Pie Charts
   - Donut Charts
   - Bar Charts
   - Word Clouds
   - Filter Slicers for Date, Vendor, Customer, and Product

---

## 📊 Key Insights

Based on the analysis shown in the dashboards:

- **Most Sold Product by Quantity:**  
  Habanero Peppers led in terms of total quantity sold (1103 units).

- **Top Product by Revenue:**  
  Poblano Peppers generated the highest revenue (1.1K sales).

- **Best Customers:**  
  - **Deanna Washington** and **Manuel Diaz** consistently appeared in both high sales and high quantity.
  
- **Single Vendor Dominance:**  
  All sales and quantities were handled by a single vendor (vendor_id: 7).

- **Customer Distribution by ZIP:**  
  ZIP code **22800** had the highest number of purchases.

---

## 📸 Dashboard Snapshots

### 💰 Sales Dashboard  
![Sales Dashboard](./34d7c91d-ee0a-4bc1-9372-d027984ecedd.png)

### 📦 Quantity Dashboard  
![Quantity Dashboard](./d1bc2c8b-30c7-46ea-9105-30329c936127.png)

---

## 💡 Tools Used

- **Power BI**
- **DAX**
- **Data Modeling (Star Schema)**
- **CSV Dataset**

---



## ✅ Future Improvements

- Include multiple vendors and product categories
- Automate data refresh using scheduled updates
- Add drill-through pages for deep dives
