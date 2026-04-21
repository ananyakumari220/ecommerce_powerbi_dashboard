# 🛒 E-Commerce Sales Analysis Dashboard (Power BI)

## 📌 Project Overview
This project presents an end-to-end **Power BI dashboard** for analyzing e-commerce sales data across India for FY 2024.

It includes:
- 150 transactions dataset
- 22 custom DAX measures
- 4 interactive dashboard pages
- Custom dark theme

---

## 🎯 Business Objectives
- Track revenue, profit, and orders
- Identify top products & customers
- Analyze payment modes & returns
- Monitor growth (MoM, QoQ, YTD)
- Enable filtering by region, category, and time

---

## 📂 Project Files


---

## 📊 Dataset Details
- **Rows:** 150  
- **Columns:** 20  
- **Region:** India  
- **Categories:** Electronics, Furniture, Clothing, Beauty, Grocery  

### Key Metrics
| Metric | Value |
|------|------|
| Total Revenue | ₹1.74 Cr |
| Total Profit | ₹34.8 L |
| Orders | 150 |
| Customers | 126 |
| Profit Margin | 20.1% |

---

## ⚙️ Setup Instructions

### Prerequisites
- Power BI Desktop
- Python 3.8+
- pandas, matplotlib
- Node.js (optional)

### Steps
1. Open Power BI Desktop  
2. Load CSV dataset  
3. Apply Power Query transformations  
4. Add DAX measures  
5. Load `.pbix` file  
6. Map visuals manually  
7. Save report  

---

## 🔄 Data Transformations
- Date formatting  
- Shipping days calculation  
- Month & quarter extraction  
- Profit margin calculation  
- Return flag creation  
- Sales band categorization  

---

## 📈 Key DAX Measures

### Core Metrics
- Total Revenue
- Total Profit
- Total Orders
- Quantity Sold

### KPIs
- Profit Margin %
- Avg Order Value
- Return Rate %
- Net Revenue

### Time Intelligence
- YTD Revenue
- MTD Revenue
- QoQ Growth
- MoM Growth

---

## 📊 Dashboard Pages

### 1. Overview
- KPI cards
- Revenue trends
- Category & region analysis

### 2. Product Analysis
- Sales vs Profit scatter
- Category treemap
- Product table

### 3. Customer Analysis
- Top customers
- Segment distribution
- Payment breakdown

### 4. Time Intelligence
- YTD trends
- Quarterly revenue
- Growth analysis

---

## 🎨 Custom Theme
- Background: `#0F1117`
- Primary: Blue
- Positive: Green
- Negative: Red

---

## 🐍 Python Visual
Includes a **Sales vs Profit scatter plot with regression line**

### Setup:
1. Enable Python in Power BI  
2. Install dependencies:
```bash
pip install matplotlib numpy pandas
