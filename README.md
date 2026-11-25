# NexoKart-E-Commerce-Sales-Dashboard---Power-BI
Interactive NEXOKART E-Commerce Sales Dashboard built using Power BI to analyze sales performance, profit trends, product categories, customer purchasing behavior, payment methods, and state-wise revenue. Provides actionable business insights through interactive visualizations and KPI tracking.
<div align="center">

# 🛒 NexoKart E-Commerce Sales Dashboard

**An interactive Power BI dashboard that turns raw e-commerce orders into clear sales, profit and customer insights.**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blueviolet?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-1f6feb?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

[![NexoKart Dashboard](screenshots/dashboard.png)](https://app.powerbi.com/view?r=YOUR_LINK_HERE)

### [🔗 Open the live interactive dashboard](https://app.powerbi.com/view?r=YOUR_LINK_HERE)
_Click the image or the link above to filter by quarter and explore every chart._

</div>

---

## 📑 Table of Contents
- [About the Project](#-about-the-project)
- [Key Metrics](#-key-metrics)
- [Dashboard Features](#-dashboard-features)
- [Key Insights](#-key-insights)
- [Data Model](#-data-model)
- [Tools & Skills](#-tools--skills)
- [How to Run](#-how-to-run)
- [Repository Structure](#-repository-structure)
- [Author](#-author)

---

## 📌 About the Project

NexoKart is an online retail business selling **Clothing, Electronics and Furniture** to customers across India. This one-page Power BI report gives management a fast answer to:

- How much revenue and profit are we making?
- Which months, categories and sub-categories drive (or hurt) profit?
- How do customers prefer to pay?
- Which states and customers contribute the most?

## 📊 Key Metrics

| 💰 Total Amount | 📈 Total Profit | 📦 Total Quantity | 🧾 AOV |
|:---:|:---:|:---:|:---:|
| **438K** | **37K** | **6K** | **121K** |

## ✨ Dashboard Features

- **Quarter slicer (Qtr 1 – Qtr 4)** and a **dropdown filter** that update every visual at once
- **Cross-filtering**: click any bar or donut slice to highlight related data across the page
- **KPI cards** for Amount, Profit, Quantity and AOV
- **Profit by Month** column chart, with loss-making months in a contrasting colour
- **Sales by State** and **Top Customers** bar charts
- **Category** and **Payment Mode** donut charts
- **Profit by Sub-Category** ranking
- Custom dark theme with gradient background and brand logo

## 🔍 Key Insights

<details open>
<summary><b>Click to expand / collapse</b></summary>

- 👕 **Clothing dominates volume**: 63% of units sold, followed by Electronics (21%) and Furniture (17%).
- 💳 **Cash on Delivery is the most popular payment mode (44%)**, ahead of UPI (21%), Debit Card (13%), Credit Card (12%) and EMI (10%).
- 🗺️ **Maharashtra leads revenue**, followed by Madhya Pradesh, Uttar Pradesh and Delhi.
- 🖨️ **Printers and Bookcases are the most profitable sub-categories**, ahead of Saree, Accessories and Tables.
- 📅 **Profit is uneven across the year**: strong from January to April and again in November, with losses in May, July, September and December.
- 👤 **Top customers** (Harivansh, Madhav, Madan Mohan and Shiva) each contribute roughly 6K–10K in sales.

</details>

<details>
<summary><b>💡 Recommendations</b></summary>

- Investigate the loss-making months (May, July, September, December) for discounting or return issues.
- Promote UPI and card payments to reduce reliance on Cash on Delivery, which carries higher returns and handling risk.
- Expand marketing in lower-revenue states such as Delhi and Uttar Pradesh.
- Stock more of the high-profit sub-categories such as Printers and Bookcases.

</details>

## 🗂️ Data Model

| Table | Description |
|---|---|
| **Orders** | Order-level data: order date, customer name, state |
| **Details** | Line-level data: category, sub-category, amount, profit, quantity, payment mode |

**Measures:** `Amount`, `Profit`, `Quantity`, `AOV`

## 🛠️ Tools & Skills

- **Power BI Desktop**: report design and interactivity
- **DAX**: calculated measures
- **Power Query**: data cleaning and transformation
- **Data modelling**: relating the Orders and Details tables
- **Data storytelling**: KPI cards, ranking charts and slicers

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/nexokart-ecommerce-sales-dashboard.git
   ```
2. Open `NEXOKART_ECOMMERCE_SALES_DASHBOARD.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
3. Use the quarter slicer and click on charts to explore the data.

## 📁 Repository Structure

```
nexokart-ecommerce-sales-dashboard/
├── NEXOKART_ECOMMERCE_SALES_DASHBOARD.pbix
├── NEXOKART_ECOMMERCE_SALES_DASHBOARD.pdf
├── screenshots/
│   └── dashboard.png
└── README.md
```

## 👤 Author

**Your Name**
[LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)

---

<div align="center">⭐ If you like this project, please give it a star! ⭐</div>
