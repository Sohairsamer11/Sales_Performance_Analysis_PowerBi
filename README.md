
# 📊 Sales Performance Analysis Report | Power BI

An end-to-end sales analytics project built with **Power BI** to analyze sales performance, profitability, product trends, discounts, geographic performance, costs, and sales forecasting.

The project transforms raw sales data into an interactive **8-page dashboard** to support data-driven business decisions.

---

## 📌 Project Overview

This project explores sales performance and profitability across products, categories, and markets. It analyzes **4,116 orders, 1,810 products, 17 sub-categories, and 3 product categories** to answer key business questions:

- How much revenue and profit does the business generate?
- Which product categories and sub-categories perform best?
- How do sales and profits change over time?
- How do discounts affect profitability?
- Which countries generate the highest sales?
- What are the main cost and quantity trends?
- What do historical sales trends suggest about future performance?

## 🎯 Objectives

- Build an interactive Power BI report for business users.
- Track key performance indicators (KPIs), including sales, profit, quantity, cost, and average order value.
- Compare performance across product categories, sub-categories, and geographic markets.
- Analyze sales trends over time.
- Explore the relationship between discounts and profitability.
- Present findings through clear, interactive visualizations.
- Use historical sales data to explore potential future trends.

## 📂 Repository Structure

```text
Sales_Performance_Analysis_PowerBi/
├── Sohair Samer Yehia PowerBi Project.pbix
├── Power BI - Sales Project Data - Un-cleaned.xlsx
├── images/
│   ├── 01-descriptive-statistics.PNG
│   ├── 02-time-series-analysis.PNG
│   ├── 03-product-category-analysis.PNG
│   ├── 04-discount-profitability.PNG
│   ├── 05-orders-quantity.PNG
│   ├── 06-geographic-analysis.PNG
│   ├── 07-cost-analysis.PNG
│   └── 08-forecasting.PNG
└── README.md
```

## 📑 Report Pages

| Page | Analysis | Focus |
|---|---|---|
| 1 | Descriptive Statistics | Overview of key performance indicators and descriptive statistics |
| 2 | Time-Series Analysis | Sales trends and changes over time |
| 3 | Product & Category Analysis | Performance by product, category, and sub-category |
| 4 | Discount & Profitability Analysis | Discount patterns and their relationship with profit |
| 5 | Orders & Quantity Analysis | Order volume and quantity trends |
| 6 | Geographic Sales Analysis | Sales performance across geographic markets |
| 7 | Cost Analysis | Cost patterns and comparisons |
| 8 | Forecasting | Historical sales patterns and potential future trends |

## 🔍 Key Findings

- **Overall sales:** Approximately $2.35 million.
- **Total profit:** Approximately $283.16K.
- **Total cost:** Approximately $2.06 million.
- **Total quantity sold:** 30,337 units.
- **Total orders:** 4,116.
- **Product portfolio:** 1,810 products across 17 sub-categories and 3 categories.

### Category Performance

- **Furniture:** Approximately $650K in sales, with a profit of $52K and a profit margin of around 8%.
- **Office Supplies:** Approximately $823K in sales, with a profit of $125K and a profit margin of around 15%.
- **Technology:** Approximately $874K in sales, with a profit of $106K and a profit margin of around 12%.

### Additional Observations

- Office Supplies accounts for the largest share of units sold, with approximately 19,888 units.
- Technology generated approximately $874K in sales.
- Furniture has a lower profit margin than the other two categories, making its profitability worth further investigation.
- Discount analysis can help identify whether higher discounts are associated with lower profitability.
- Geographic analysis helps compare sales performance across markets.

*Note: Figures are based on the project's reported dashboard values and may be affected by the underlying dataset and its coverage.*

## 🗃️ Dataset

The project uses the provided Excel workbook:

`Power BI - Sales Project Data - Un-cleaned.xlsx`

The workbook contains the following data tables or sheets:

- Order Details
- Orders
- Sub-Category
- Ship Mode
- Product
- Customer
- Country
- City
- Category

The data supports analysis of orders, products, customers, sales, quantities, costs, discounts, profits, and geographic performance.

## 🛠️ Tech Stack

- **Power BI Desktop:** Report development and data visualization.
- **DAX:** Measures and KPI calculations.
- **Power Query:** Data cleaning and transformation.
- **Microsoft Excel:** Source data and data inspection.
- **Data Modeling:** Organizing relationships between data tables.
- **Time-Series Analysis:** Exploring historical sales trends.
- **Forecasting:** Examining potential future sales patterns.

## 🚀 How to Use

1. Download or clone this repository.
2. Open `Sohair Samer Yehia PowerBi Project.pbix` using Power BI Desktop.
3. If Power BI requests the source data location, reconnect it to `Power BI - Sales Project Data - Un-cleaned.xlsx`.
4. Refresh the data if needed.
5. Navigate through the eight report pages to explore the analysis.
6. Refer to the `images/` folder to preview the dashboard pages.

## ⚠️ Limitations & Next Steps

- **Data coverage:** The completeness of the 2015 data should be checked before drawing conclusions about year-over-year performance.
- **Discount analysis:** Further investigation may be needed to distinguish the effects of discounts from other factors influencing profitability.
- **Forecast uncertainty:** Forecasts are estimates based on historical patterns and should not be treated as guaranteed future outcomes.
- **Potential extensions:**
  - Customer segmentation and purchasing behavior analysis.
  - More detailed profitability analysis by product and market.
  - Additional sales and operational KPIs.
  - Forecast accuracy evaluation using a separate validation period.
  - Automated data refresh and reporting.

## 🖼️ Dashboard Screenshots

### 1. Descriptive Statistics

![Descriptive Statistics](images/01-descriptive-statistics.PNG)

### 2. Time-Series Analysis

![Time-Series Analysis](images/02-time-series-analysis.PNG)

### 3. Product & Category Analysis

![Product & Category Analysis](images/03-product-category-analysis.PNG)

### 4. Discount & Profitability Analysis

![Discount & Profitability Analysis](images/04-discount-profitability.PNG)

### 5. Orders & Quantity Analysis

![Orders & Quantity Analysis](images/05-orders-quantity.PNG)

### 6. Geographic Sales Analysis

![Geographic Sales Analysis](images/06-geographic-analysis.PNG)

### 7. Cost Analysis

![Cost Analysis](images/07-cost-analysis.PNG)

### 8. Forecasting

![Forecasting](images/08-forecasting.PNG)

## 👩‍💻 Author

**Sohair Samer Yehia** — Data Analyst

- [LinkedIn](https://www.linkedin.com/in/sohair-samer)
- [GitHub](https://github.com/Sohairsamer11)
