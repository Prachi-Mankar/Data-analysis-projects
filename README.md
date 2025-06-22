# 🛒 Ecommerce Data Analysis with MySQL and Python

This project performs an end-to-end data analysis on a Brazilian ecommerce dataset using SQL queries and Python-based visualizations. The objective is to extract business insights, understand customer behavior, and uncover product and sales performance trends.

---

## 📦 Dataset Description

The dataset consists of multiple CSV files, including:

- `customers.csv` – Customer details
- `orders.csv` – Order timeline
- `order_items.csv` – Products per order
- `products.csv` – Product categories
- `payments.csv` – Payment methods and amounts
- `sellers.csv` – Seller metadata
- `geolocation.csv` – Geo-coordinates for regions

These files were imported into a MySQL database (`ecommerce`) using a Python automation script.

---

## ⚙️ Technologies Used

- **Python**: Data handling and visualization
- **MySQL**: Querying and relational joins
- **Pandas**: Data wrangling
- **Seaborn & Matplotlib**: Plotting and insights
- **Jupyter Notebook**: Analysis environment

---

## 📊 Analysis Highlights

### 📈 Sales & Revenue
- 💵 **Total sales per product category**
- 📊 **Monthly cumulative revenue (2016–2018)**
- 📉 **Year-over-Year (YoY) sales growth**
- 📦 **Seller-wise revenue ranking**
- 📌 **Correlation between price and product sales**

### 🛍 Customer Insights
- 🏙 **Unique customer cities and states**
- 🗓 **Monthly order count in 2018**
- 🧮 **Average products per order by city**
- 💳 **% Orders paid via installments**: 99.99%
- 🔁 **Customer retention (within 6 months)** *(in progress)*

### 🏆 Top Customers
- 🥇 **Top 3 customers by yearly spend**
- 📈 **Moving average of order value per customer**

---

## 📈 Sample Visualization

- Bar plots for order trends
- Revenue by category and state
- Top spending customers by year

---

## 📂 Project Structure

