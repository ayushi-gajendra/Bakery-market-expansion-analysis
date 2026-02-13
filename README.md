# 🥖 Bakery Sales Analysis: Market Validation Study
### *Bridging Data Insights and Stakeholder Expectations*

![Data Analysis](https://img.shields.io/badge/Analysis-Data%20Analytics-blue)
![Business Intelligence](https://img.shields.io/badge/Domain-Business%20Intelligence-green)
![Google Sheets](https://img.shields.io/badge/Tools-Google%20Sheets-success)
![Excel](https://img.shields.io/badge/Tools-Microsoft%20Excel-orange)

---

## 🎯 Project Overview
This project is a **Market Validation Study** for a bakery in South Korea. The goal was to use real sales data to guide a new investor's strategy. 

A key stakeholder was convinced that the business should focus almost entirely on **Croissants**. By analyzing over $2,400$ transaction records, I tested this theory against actual customer behavior to find the most profitable path forward.

---

## 🛠️ The Business Problem
As a consultant with an entrepreneurial background, I needed to solve three main issues:
1. **Fact-Checking:** Was the investor's focus on croissants backed by data?
2. **Growth:** Which products are the true "stars" that drive the most revenue?
3. **Efficiency:** How can we change staffing and inventory to match peak "Rush Hours"?

---

## ⚙️ Methodology: The Data Analytics Lifecycle
I followed a structured $5$-step process to ensure the results were accurate and professional.

### 1. Data Cleaning & Preparation
I processed a raw dataset of $2,420$ transactions to make it "analysis-ready":
* **Categorization:** Created new columns for `Food Items` and `Drinks` to analyze buying habits separately.
* **Time Formatting:** Extracted `Hour` and `Day of Week` from timestamps to identify specific "Rush Hour" patterns.

### 2. Time-Series Analysis (Operational Efficiency)
I analyzed income trends to help the business plan for peak demand.
* **Technique:** Used `SUMIF` and Pivot Tables to calculate total revenue per hour.
* **Result:** Discovered that the "Golden Hour" for revenue is **$11:00$ AM**.

### 3. Product Performance Audit
I tested the investor's theory by ranking every menu item by total units sold.
* **Technique:** Applied `COUNTIF` and volume-ranking to identify top-performing products.
* **Result:** Proved that **Angbutter** is the true market leader, selling **$322\%$** more units than Croissants.

### 4. Correlation & Mix Analysis
I studied the relationship between food and beverage sales to find cross-selling opportunities.
* **Technique:** Created a **$100\%$ Stacked Column Chart** to see how the "Product Mix" changes throughout the day.
* **Result:** Found that drink sales proportions increase by approximately $60\%$ in the afternoon, identifying a prime window for beverage promotions.

### 5. Insight Synthesis (Business ROI)
The final step was translating "Numbers" into "Actions" regarding inventory, labor, and revenue growth.

---

## 📂 Data Reference
**Data Source:** Modified version of the Bakery Sales dataset (Kaggle)
- https://www.kaggle.com/datasets/hosubjeong/bakery-sales/data

**Fields included in the dataset:**
* **Temporal:** `datetime` (Order time), `day of week`, `year`, `month`, `day`, `hour`.
* **Financial:** `total` (Purchase amount in Korean Won).
* **Bakery Items:** Angbutter, Plain Bread, Jam, Croissant, Tiramisu Croissant, Cacao Deep, Pain au Chocolate, Almond Croissant, Croque Monsieur, Mad Garlic, Pandoro, Cheese Cake, Orange Pound, Wiener, Tiramisu, Meringue Cookies.
* **Beverages:** Americano, Caffe Latte, Milk Tea, Lemon Ade, Vanila Latte, Berry Ade.

---

## 📊 Live Dashboards
I built this analysis using **Google Sheets** and **Excel** to ensure the data is easy for stakeholders to access and understand.

👉 **[View the Live Google Sheets Analysis here](TO_BE_INSERTED)** *(Set to View-Only)*

---

## 💡 Strategic Recommendations
1. **Smart Inventory:** Increase Angbutter production capacity by $50\%$ on weekends to prevent stock-outs of the primary revenue driver.
2. **Dynamic Staffing:** Shift $70\%$ of labor hours to the **$10:00$ AM – $1:00$ PM** window to handle the morning rush.
3. **Product Bundling:** Launch a **"Morning Rush" bundle** (Angbutter + Americano) to increase the Average Order Value (AOV).

---

## 🧱 Project Structure
```bash
├── data/
│   └── bakery_sales_raw.csv         # Transactional dataset
├── analysis/
│   └── bakery_logic_models.xlsx     # Pivot tables & trend calculations
├── visuals/
│   └── sales_dashboards.png         # Key visualizations
└── README.md                        # Project documentation
