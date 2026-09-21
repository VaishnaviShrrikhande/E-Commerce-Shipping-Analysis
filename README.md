# E-Commerce Shipping Analysis

## 📌 Project Overview

This project analyzes e-commerce shipping data to understand **delivery performance, customer satisfaction, warehouse performance, and shipping patterns**.

SQL was used for data exploration, cleaning, and analysis, while Power BI was used to create interactive dashboards and visualize key business insights.

## 🎯 Objectives

- Analyze on-time and delayed deliveries
- Identify warehouse and shipment mode performance
- Understand customer satisfaction and ratings
- Analyze discounts and their relationship with delivery performance
- Identify patterns that can help improve shipping operations
- Build interactive Power BI dashboards for business reporting

## 📊 Dataset

The dataset was sourced from **Kaggle** and contains:

- **10,999 records**
- **12 attributes**
- Customer, product, warehouse, shipping, discount, and delivery information

### Key Columns

| Column | Description |
|---|---|
| ID | Unique customer identifier |
| Warehouse Block | Warehouse location/block |
| Mode of Shipment | Ship, Flight, or Road |
| Customer Care Calls | Number of customer calls |
| Customer Rating | Rating from 1 to 5 |
| Cost of Product | Product price |
| Prior Purchases | Number of previous purchases |
| Product Importance | Low, Medium, or High |
| Gender | Customer gender |
| Discount Offered | Discount provided |
| Weight in Grams | Product weight |
| Reached on Time | Delivery status |

## 🛠️ Tools & Technologies

- **SQL** – Data exploration, preprocessing, and analysis
- **Power BI** – Data visualization and interactive dashboards
- **Kaggle Dataset** – E-commerce shipping data

## 🔍 SQL Analysis

The SQL analysis focused on:

- Data quality and duplicate checks
- Warehouse shipment distribution
- Shipment mode analysis
- Customer rating analysis
- On-time vs. delayed deliveries
- Average discount by delivery status
- Warehouse and shipment delay analysis
- Product weight and delivery performance
- Customer care calls and delivery delays

## 📈 Power BI Dashboards

### Dashboard 1: Overall E-Commerce Performance

This dashboard provides an overview of:

- Revenue and overall performance
- Customer ratings
- Product importance
- Gender distribution
- Warehouse performance
- Customer service interactions
- Product cost and weight

### Dashboard 2: Shipping Performance Analysis

This dashboard focuses on:

- On-time vs. delayed deliveries
- Shipment mode performance
- Warehouse delivery performance
- Average discount by delivery status
- Product cost and delivery status
- Customer care calls

## 💡 Key Insights

- **6,563 deliveries were delayed**, compared with **4,436 on-time deliveries**.
- Delayed deliveries had a higher average discount compared with on-time deliveries.
- Warehouse and shipment mode analysis showed differences in delivery performance.
- Heavier products showed an association with higher delivery delays.
- Flight had the highest delay percentage among the three shipment modes, although the differences were relatively small.
- Customer care call patterns showed differences in delivery delay percentages.

These insights can help businesses identify areas for improving **logistics, warehouse operations, customer service, and delivery efficiency**.

## 📌 Business Recommendations

Based on the analysis:

- Monitor warehouses with higher delay rates.
- Investigate causes of shipment delays.
- Review the relationship between product weight and delivery performance.
- Analyze discount strategies for delayed orders.
- Improve logistics and customer service processes.
- Use predictive analytics to identify shipments at risk of delay.

## 📂 Project Structure

```text
E-Commerce-Shipping-Analysis/
│
├── SQL/
│   └── SQL Queries
│
├── PowerBI/
│   └── Power BI Dashboard
│
├── Dataset/
│   └── E-commerce Shipping Data
│
└── README.md
```

## 🚀 Future Enhancements

- Build a predictive model for delayed shipments
- Develop real-time shipment tracking
- Integrate additional datasets
- Create automated reporting
- Add advanced Power BI KPIs and measures

Data Analyst | SQL | Power BI | Data Analysis
