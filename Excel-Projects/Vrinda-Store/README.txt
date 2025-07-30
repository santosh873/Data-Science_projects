## 🛍️ Vrinda Store Sales Report (Excel Dashboard Project)

This project is an Excel-based sales analysis dashboard for a fictional retail brand, **Vrinda Store**. It involves data cleaning, transformation, and visualization using Excel features like formulas, pivot tables, charts, and slicers.



## 📁 Dataset Overview

The original dataset includes the following columns:
Index | Order ID | Cust ID | Gender | Age | Age-group | Date | Month | Status | Channel | SKU | Category | Size | Qty | Currency | Amount | Ship-City | Ship-State | Ship-Postal-Code | Ship-Country | B2B


---

## 🧹 Data Cleaning & Transformation Steps

✅ **Gender Normalization**: Replaced shorthand values `M` and `W` with `Men` and `Women`
✅ **Created Age Group**:
  - `< 18` → **Teenage**
  - `18 - 50` → **Adult**
  - `> 50` → **Senior**
✅ **Date Format Standardization**: Converted to `YYYY-MM-DD` format and sorted from latest to oldest
✅ **Month Extraction**: Extracted month names from the date column
✅ **Quantity Normalization**: Converted values like "One" to `1`
✅ **City & State Cleanup**: Applied `TRIM()` and `PROPER()` to clean spacing and capitalize names

---

## 📊 Insights

## 📌 Top 5 Performing States (by orders/sales):
- Maharashtra
- Karnataka
- Uttar Pradesh
- Telangana
- Tamil Nadu

## 🚚 Order Status Distribution:
- Delivered – **92%**
- Cancelled – **3%**
- Returned – **3%**
- Refunded – **2%**

## 🧍 Gender-wise Sales:
- Women: **64%**
- Men: **36%**

## 📅 Monthly Trends:
- **Highest Sales**: March
- **Lowest Sales**: December

## 💰 Consumer Behavior:
- **Adult males** purchase higher value items
- **Top Channels**: Amazon & Flipkart dominate sales volume

---

## 🛠️ Tools & Features Used

- Microsoft Excel (2016+)
- Formulas: `IF()`, `TEXT()`, `PROPER()`, `TRIM()`, `VLOOKUP`, `SUMIFS`
- Pivot Tables and Pivot Charts
- Slicers for interactive filtering
- Conditional Formatting

---

## 📂 Project Files

- `Vrinda_Store_Sales_Report.xlsx` — Main Excel workbook with visuals
- `images` — Screenshots of the dashboard 

---

## 🚀 How to Use

1. Download and open `Vrinda_Store_Sales_Report.xlsx`
2. Explore dashboard using slicers by month, gender, and status
3. Review key KPIs, trend charts, and regional performance

---

## 📌 Project Status

✅ Completed for portfolio/resume  
📈 Open for future enhancement (e.g., Power BI version, advanced DAX analysis)

---

## 🧑‍💼 Author

**Santosh Patil**  
[GitHub Profile](https://github.com/yourusername)

