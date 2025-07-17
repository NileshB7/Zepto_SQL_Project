# **Zepto SQL Data Analysis – E-commerce Product Insights**

## **📌 Project Overview**
This project focuses on analyzing **Zepto’s e-commerce product data** using SQL.  
The goal is to explore inventory trends, revenue estimation, and product pricing insights to help optimize stock management and discounts.

---

## **📂 Project Files**
- **`Zepto_SQL_Data_Analysis.sql`** → SQL script containing table creation, data cleaning, and analysis queries.  
- **`zepto_v2.csv`** → Dataset containing product information.

---

## **🛠️ Tools & Technologies**
- **SQL (PostgreSQL / MySQL compatible)**  
- **Data Cleaning & Exploration** using SQL queries  
- **CSV as Data Source**

---

## **📊 Key SQL Operations**
### **1. Data Exploration**
- Checked for **null values** and duplicate product names  
- Counted **in-stock vs out-of-stock** products  
- Identified **different product categories**

### **2. Data Cleaning**
- Removed products with **MRP = 0**  
- Converted prices from **paise to rupees**

### **3. Business Analysis Queries**
✅ **Q1:** Top 10 best-value products based on highest discount percentage  
✅ **Q2:** Products with **High MRP but Out of Stock**  
✅ **Q3:** **Estimated Revenue per Category** (`SUM(discountedSellingPrice * availableQuantity)`)  
✅ **Q4:** Products with **MRP > ₹500 & discount <10%**  
✅ **Q5:** Top 5 categories with highest average discount  
✅ **Q6:** **Price per gram** calculation for products >100g  
✅ **Q7:** Categorized products as **Low, Medium, Bulk** based on weight  
✅ **Q8:** Total **Inventory Weight per Category**

---

## **🔍 Sample Insights**
- Certain **high MRP products are out of stock**, indicating potential demand  
- Categories with **bulk weight products** generate higher total inventory weight  
- Few categories consistently offer **higher average discounts**

---

## **🚀 How to Run**
1. Import `zepto_v2.csv` into your SQL database.  
2. Run `Zepto_SQL_Data_Analysis.sql` in your SQL editor (PostgreSQL or MySQL).  
3. Explore insights by running the queries individually.
