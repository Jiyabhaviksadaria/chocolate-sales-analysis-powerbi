# 🍫 Power BI – Chocolate Sales Dashboard

This project presents an interactive **Power BI Sales Dashboard** built using a chocolate sales dataset.  
The goal of this report is to transform raw data into meaningful business insights through data cleaning, modeling, DAX calculations, and visual storytelling.

## 📌 Project Objective
To analyze chocolate sales performance across different products, regions, and timelines, and to provide decision-makers with a clear understanding of:

- Total revenue & profit  
- Best-selling products  
- Region-wise performance  
- Monthly/quarterly sales trends  
- Customer purchase patterns  

## 🚀 Dashboard Features

### ✨ 1. KPI Metrics
- **Total Sales**  
- **Total Quantity Sold**  
- **Total Profit & Profit %**  
- **Average Order Value (AOV)**  
- **Year-over-Year Growth**

### ✨ 2. Product Insights
- Best-selling chocolate categories  
- Top contributing SKUs  
- Product-wise revenue and profit comparison  

### ✨ 3. Regional Analysis
- City-wise revenue visualization  
- Regional sales heatmap  
- High and low performing areas  

### ✨ 4. Trend Analysis
- Month-wise and quarter-wise sales trends  
- Seasonality patterns  
- Growth visualization over time  

### ✨ 5. Customer Insights
- Customer-wise revenue contribution  
- Order frequency patterns  
- Identification of high-value customers  

## 🛠 Tech Stack & Tools
- **Power BI Desktop**  
- **Power Query Editor**  
- **Data Modeling (Star Schema)**  
- **DAX (Data Analysis Expressions)**  
- **Excel (Dataset)**  

## 📂 Dataset Overview
The dataset includes fields such as:

- Order ID  
- Date  
- Product Category  
- Product Name  
- Quantity  
- Unit Price  
- Total Sales  
- Profit  
- Region / City  
- Customer Name / ID  

This dataset simulates a retail business environment, ideal for sales reporting and trend analysis.

## 📘 Sample DAX Measures
```DAX
Total Sales = SUM(Sales[Total_Sales])

Total Quantity = SUM(Sales[Quantity])

Total Profit = SUM(Sales[Profit])

Profit % = DIVIDE([Total Profit], [Total Sales])

Average Order Value = DIVIDE([Total Sales], DISTINCTCOUNT(Sales[Order_ID]))
```

## 📁 Repository Contents
- `Chocolate_Sales_Dashboard.pbix` – Power BI report  
- `sample-sales-data.xlsx` – Dataset  
- `README.md` – Documentation  

## 🎯 Key Learnings
- Hands-on experience creating BI dashboards  
- Practical understanding of data cleaning & ETL  
- Developing DAX measures for business KPIs  
- Visual storytelling using Power BI  
- Analyzing and interpreting business performance

## 👩‍💻 About Me
**Jiya Sadaria**  
AIML Engineering Student | Aspiring Data Analyst & BI Developer  

Excited to work on more projects in Data Analytics, ML, and Business Intelligence!

## 🔗 Connect With Me
- **LinkedIn:** Add your link  
- **GitHub:** Add your repository link  
- **Email:** jiyasadaria@gmail.com  
