# **Finance Performance Analysis Dashboard**

## **Project Overview**
[cite_start]The objective of this project is to analyze global financial metrics across various segments and countries using **Power BI**[cite: 5]. [cite_start]It transforms raw financial data into a professional dashboard to provide stakeholders with actionable business insights for optimizing global sales strategies[cite: 92].

---

## **Tech Stack & Tools**
* [cite_start]**Data Visualization:** Power BI Desktop [cite: 1, 58]
* [cite_start]**Data Processing:** MS Excel [cite: 1]
* [cite_start]**Query Language:** DAX (Data Analysis Expressions) [cite: 1]
* [cite_start]**Role:** Business Analyst [cite: 1]
* [cite_start]**Project Level:** Intermediate [cite: 1]

---

## **Key Business Metrics (KPIs)**
The dashboard tracks three primary high-level numbers to monitor organizational health:
* [cite_start]**Total Revenue:** $118.73M [cite: 63, 113]
* [cite_start]**Total Profit:** $16.89M [cite: 36, 117]
* [cite_start]**Total Units Sold:** 1.13M units [cite: 28, 118]

---

## **Dataset Description**
[cite_start]The analysis is based on a comprehensive financial dataset [cite: 2] containing the following key attributes:
* [cite_start]**Market Segments:** Government, Midmarket, Channel Partners, Enterprise, and Small Business[cite: 8].
* [cite_start]**Geographies:** Canada, Germany, France, Mexico, and USA[cite: 9].
* [cite_start]**Product Details:** Includes products like Paseo, VTT, and Montana[cite: 10].
* [cite_start]**Financial Breakdown:** Units Sold, Manufacturing Price, Sale Price, Gross Sales, Discounts, COGS, and Profit[cite: 12, 13, 14, 15, 16, 17, 18, 19].
* [cite_start]**Time Period:** Temporal data categorized by Date, Month, and Year[cite: 20].

---

## **Dashboard Architecture**
The report is structured into three strategic layers:
1. [cite_start]**Top Layer (Executive Summary):** KPI cards for immediate visibility of Sales, Profit, and Volume[cite: 23, 24].
2. [cite_start]**Middle Layer (Categorical Analysis):** * **Waterfall Chart:** Analyzes the Sum of Profit by Segment[cite: 40, 69].
    * [cite_start]**Bar Charts:** Compares Sales by Country and Profit by Segment[cite: 44, 48].
3. [cite_start]**Bottom Layer (Interactivity):** Dynamic slicers for Country, Product, Month, and Year to allow deep-dive analysis[cite: 52, 53].

---

## **DAX Measures Used**
```dax
// Calculate Total Units Sold
Total Units Sold = SUM('financial_data'[Units Sold]) [cite: 27]

// Calculate Total Gross Sales
Total Gross Sales = SUM('financial_data'[Gross Sales]) [cite: 31]

// Calculate Total Profit
Total Profit = SUM('financial_data'[Profit]) [cite: 35]

