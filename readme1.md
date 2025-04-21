# 🛍️ Superstore Sales Analysis – Power BI Project

## 📖 About

This project is a sales analysis dashboard created in **Power BI** using the Superstore dataset. The dashboard provides key insights into sales, profit, and customer behavior across regions, categories, and segments.  
This case study focuses on improving business decisions through interactive visualizations.

---

## 🎯 Objective

To analyze sales and profitability trends of a fictional Superstore and uncover:
- Which regions and categories are most profitable?
- What customer segments drive the most revenue?
- Where are the business losses happening?

---

## 🗂️ Data Source

- **Dataset**: [Kaggle – Superstore Sales Data](https://www.kaggle.com/datasets/sudarshanbhukebag/superstores)  
- **Fields include**: `Order ID`, `Product`, `Category`, `Sales`, `Profit`, `Region`, `Customer Segment`, `Discount`, etc.

---

## 🧩 Data Model

Here’s a visual representation of the data model used in Power BI:

![Data Model](images/data_model.png)

- **One table model** (flat structure)
- Relationships manually created where needed (e.g., segment hierarchy)

---

## 📐 Measures and Calculations

Custom DAX measures created:
```DAX
Total Sales = SUM('Orders'[Sales])
Total Profit = SUM('Orders'[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```

## 🔍 Key Insights

🔸 Technology is the top-performing category by profit.

🔸 Central region had the highest sales but lower profit margins due to discounts.

🔸 Consumer segment drives the most revenue but has high return rates.

🔸 Losses often occur on high-discount products.

## 📊 Dashboard Screenshots
📌 Overview Page

🔍 Region Performance

## 🛠️ Tools Used
Power BI Desktop

DAX for custom measures

Kaggle for data

Snagit / Power BI Export for screenshots

## 👨‍💻 Author
Ons HAMMEMI
🔗 LinkedIn
