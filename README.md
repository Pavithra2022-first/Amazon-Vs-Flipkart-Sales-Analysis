# E- Commerece Sales Analytics - Comparative Analysis of Amazon And Flipkart Sales
This project compares sales performance, customer behavior, product trends, and payment preferences between Amazon and Flipkart for the year 2025.

# 📊 E- Commerece Sales Analytics - Comparative Analysis of Amazon And Flipkart Sales

## 📌 Project Overview

The **Amazon vs Flipkart Sales Analysis** project compares sales performance, customer purchasing behavior, product trends, and payment preferences across two major e-commerce platforms.

The project demonstrates an end-to-end Data Analytics workflow, including data cleaning, preprocessing, exploratory data analysis (EDA), visualization using Python, and dashboard development in Power BI.

---

## 🎯 Project Objectives

- Compare Amazon and Flipkart sales performance.
- Analyze customer purchasing behavior.
- Identify top-selling products and product categories.
- Study payment method preferences.
- Analyze monthly sales trends.
- Compare customer ratings between both platforms.
- Build an interactive Power BI dashboard.
- Generate business insights to support decision-making.

---

## 🏢 Domain

**E-Commerce Analytics**

---

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- DAX
- GitHub

---

## 📂 Dataset Information

### Amazon Dataset

- Product Name
- Product Category
- Quantity
- Unit Price
- Total Sales
- Payment Method
- Delivery Status
- Customer Rating
- Review Text
- City
- Country

### Flipkart Dataset

- Order ID
- Customer ID
- Product Name
- Product Category
- Quantity
- Unit Price
- Total Sales
- Payment Method
- Customer Rating
- City
- Country

After cleaning and preprocessing, both datasets were standardized and merged into a single dataset for comparative analysis.

---

# 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed using Python (Pandas):

- Imported Amazon and Flipkart datasets.
- Checked dataset structure using:
  - `head()`
  - `tail()`
  - `shape`
  - `info()`
  - `describe()`
- Checked duplicate records.
- Checked missing values.
- Converted numerical columns into appropriate data types.
- Filled missing numerical values using product-wise averages from existing products and overall mean where required.
- Filled missing categorical values using suitable replacement values.
- Calculated missing **Total Sales** using:

```
Total Sales = Quantity × Unit Price
```

- Standardized column names between both datasets.
- Added a **Platform** column to identify Amazon and Flipkart records.
- Merged both datasets into one final dataset.

---

# 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Platform-wise Sales Analysis
- Monthly Sales Trend
- Product Category Analysis
- Top Selling Products
- Customer Rating Analysis
- Payment Method Analysis
- City-wise Sales Analysis
- Correlation Analysis

---

# 📈 Visualizations

The project includes the following visualizations:

1. Platform-wise Sales Comparison (Bar Chart)
2. Sales Contribution by Platform (Pie Chart)
3. Unit Price vs Total Sales (Scatter Plot)
4. Customer Rating Distribution (Box Plot)
5. Top 10 Products by Sales (Horizontal Bar Chart)
6. Correlation Heatmap
7. Monthly Sales Trend (Area Chart)
8. Category-wise Sales Comparison (Stacked Bar Chart)

---

# 📊 Power BI Dashboard

The dashboard was developed using Power BI Desktop.

### Dashboard Features

- KPI Cards
  - Total Sales (Amazon)
  - Total Sales (Flipkart)
  - Average Sales (Amazon)
  - Average Sales (Flipkart)

- Platform-wise Sales

- Monthly Sales Trend

- Product Category Analysis

- Payment Method Distribution

- City-wise Sales Analysis

- Top Products Analysis

- Interactive Filters
  - Platform
  - Month
  - Quarter

---

# 📷 Dashboard Preview

## Overall Dashboard

<img width="975" height="541" alt="image" src="https://github.com/user-attachments/assets/c926cddc-86a1-4f53-9716-fe532ceaa714" />


---

## Amazon Dashboard (Filtered)

<img width="1013" height="422" alt="image" src="https://github.com/user-attachments/assets/25b28a10-0525-4bf1-8027-912a0f6b9364" />


---

## Flipkart Dashboard (Filtered)

<img width="1013" height="428" alt="image" src="https://github.com/user-attachments/assets/0ee38567-41c9-4c71-982b-040e7b5e4066" />

---

# 💡 Key Business Insights

- Amazon generated slightly higher total sales than Flipkart.
- A small number of product categories contributed the majority of revenue.
- Higher quantities sold generally resulted in higher total sales.
- Customer ratings remained consistently high across both platforms.
- Digital payment methods were preferred by most customers.
- Certain cities generated significantly higher sales.
- Monthly sales trends revealed seasonal demand fluctuations.
- Interactive filters allow quick comparison between Amazon and Flipkart.

---

# 📌 Business Recommendations

- Focus marketing campaigns on top-performing product categories.
- Maintain sufficient inventory for high-demand products.
- Increase promotions in high-performing cities.
- Encourage digital payments through offers and cashback.
- Use monthly sales trends for inventory planning.
- Continuously monitor customer ratings to improve customer satisfaction.

---

# 🚀 Future Scope

- Sales Forecasting using Machine Learning
- Customer Segmentation
- Product Recommendation System
- Real-time Dashboard
- Predictive Analytics
- Integration with Live E-commerce APIs

---
# 🎓 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Intelligence
- Dashboard Development
- Power BI
- DAX
- Python Programming
- Pandas
- Data Storytelling

---

# 📬 Contact

**Pavithra E**

- 📧 Email: pavieswaran2001@gmail.com
- 💼 LinkedIn: https://www.linkedin.com/in/pavithraeswaran2501/


---

⭐ If you found this project useful, feel free to fork the repository or leave a star!
