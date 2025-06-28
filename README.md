# 🛒 E-Commerce Sales Analysis Dashboard

**Project Type:** End-to-End Business Analytics  
**Tech Stack:** SQL · Python · Power BI  
**Duration:** 3 Weeks  

## 📌 Project Objective

This project was executed as a **Business Analytics initiative** for a mid-sized e-commerce company aiming to improve sales performance and customer retention through **data-driven insights**.

### 🎯 Key Goals:
- Analyze **customer behavior** and purchasing patterns across time, geography, and product categories.
- Apply **RFM Segmentation** to classify customers (e.g., loyal champions, one-time buyers, at-risk users).
- Build an **interactive Power BI dashboard** for business stakeholders.
- Provide strategic **growth recommendations** using insights from transactional data.

---

## 🧰 Tools & Technologies Used

| Tool      | Purpose                                         |
|-----------|-------------------------------------------------|
| SQL       | Data cleaning, joins, transformation            |
| Python    | EDA, RFM analysis, visualizations               |
| Power BI  | Dashboard development & interactive reporting   |
| Pandas, Matplotlib, Seaborn | Data processing and plotting |

---
## 🔁 Workflow Overview

### 1. Data Collection & Understanding
- Realistic e-commerce dataset with **~99K customers** and **135K+ order items**
- Data covers **product orders**, **payments**, **reviews**, and **customer info**

---

### 2. SQL-Based Data Cleaning
- Cleaned and joined datasets:  
  `customers`, `orders`, `order_items`, `payments`, `products`, etc.
- Filtered relevant time frame: **May 2016 – Oct 2018**

---

### 3. Python EDA & RFM Segmentation
- Data Cleaning → Merging → RFM Segmentation → Scoring

- **Recency** = Days since last order  
- **Frequency** = Number of orders per customer  
- **Monetary** = Total payment value 

---

## 📊 RFM Table:

| CustomerID                          | Recency | Frequency | Monetary | R | F | M | RFM_Score |
|-------------------------------------|---------|-----------|----------|---|---|---|-----------|
| 00012a2ce6f8dcda20d059ce98491703    | 287     | 1         | 114.74   | 2 | 1 | 3 | 6         |
| 000161a058600d5901f007fab4c27140    | 409     | 1         | 67.41    | 1 | 1 | 2 | 4         |
| 0001fd6190edaaf884bcaf3d49edf079    | 547     | 1         | 195.42   | 1 | 1 | 4 | 6         |
| 0002414f95344307404f0ace7a26f1d5    | 378     | 1         | 179.35   | 1 | 1 | 4 | 6         |
| 000379cdec625522490c315e70c7a9fb    | 149     | 1         | 107.01   | 3 | 1 | 3 | 7         |

---

## 📈 Power BI Dashboard Insights

### Dashboard Includes:
- 📅 **Monthly Orders & Revenue Trend**
- 🛍️ **Revenue by Product Category & State**
- 💳 **Payment Type Distribution**
- 👥 **RFM-Based Customer Segmentation**
- 📊 **Year-over-Year Growth**

![Screenshot 2025-06-27 164808](https://github.com/user-attachments/assets/318a2088-19b4-4f92-9ff2-204211327d1a)

## Key Analytical Insights

- Customer Spend: Most customers spend ₹50–₹300; very few spend ₹1000+
- Order Frequency: Approximately 85–90% of customers are one-time buyers
- Payment Method: Credit Cards dominate with over 75% usage
- Top Revenue States: SP, RJ, MG
- Category Leaders: Health, Watches, and Computing products

---

## Final Business Recommendations

- **Launch Loyalty Program**  
  Increase repeat purchase frequency among one-time buyers

- **Re-engagement Campaigns**  
  Target customers with high recency but low frequency

- **Upsell to High RFM Segments**  
  Offer premium bundles and exclusive deals to the top 10% of customers

- **Subscription-Based Models**  
  Target customers with high monetary value but low frequency

- **Combo & Bundling Offers**  
  Increase Average Order Value (AOV) and repeat purchases with product bundles

---

## Project Structure

/Financial_Analytics  
│  
├── SQL/  
│   └── data_cleaning_queries.sql  
│  
├── Python/  
│   └── RFM_analysis.ipynb  
│  
├── PowerBI/  
│   ├── Dashboard.pbix  
│   └── Power-Bi Dashboard.png  
│  
└── README.md  
