# **Finance Performance Analysis Dashboard**

##  **Project Overview**
This project transforms raw financial data into a professional **Power BI Dashboard** to analyze global metrics across segments and countries. It provides actionable insights to optimize sales strategies and improve profitability.

---

## **Tech Stack & Tools**
* **Visualization:** Power BI Desktop
* **Data Processing:** MS Excel
* **Language:** DAX (Data Analysis Expressions)
* **Role:** Business Analyst
* **Level:** Intermediate

---

## **Key Performance Indicators (KPIs)**
At a glance, the dashboard monitors the organization's health:
* **Total Revenue:** $118.73M
* **Total Profit:** $16.89M
* **Total Units Sold:** 1.13M

---

## **Dataset breakdown**
The analysis covers several key dimensions:
* **Segments:** Government, Midmarket, Channel Partners, Enterprise, Small Business.
* **Countries:** Canada, Germany, France, Mexico, USA.
* **Products:** Paseo, VTT, Montana, and more.
* **Metrics:** Units Sold, Manufacturing Price, Sales, COGS, and Profit.

---

## **Dashboard Architecture**
1. **Top Layer:** KPI Cards for instant visibility of big numbers.
2. **Middle Layer:** **Waterfall Chart:** Profit by Segment analysis.
                     **Bar Charts:** Sales by Country and Profit comparison.
3. **Bottom Layer:** Dynamic Slicers (Country, Product, Time) for deep-dive filtering.

---

## **DAX Measures**
```dax
// Total Units Sold
Total Units Sold = SUM('financial_data'[Units Sold])

// Total Gross Sales
Total Gross Sales = SUM('financial_data'[Gross Sales])

// Total Profit
Total Profit = SUM('financial_data'[Profit])
```

## **Business Insights & Recommendations**

Based on the analysis of the financial data, here are the key takeaways:

* **Market Leadership**: The **United States** leads in sales revenue ($25M), followed closely by **Canada** (~$25M), making North America the strongest region.
* **Profitability Drivers**: The **Government** segment is the most profitable, contributing approximately **$11M** to the total profit.
* **Operational Efficiency**: The **Small Business** segment also shows strong performance with **$4M** in profit.
* **Growth Opportunity**: The **Enterprise** segment currently shows a loss of **-$1M**. This indicates a need to review pricing strategies or reduce COGS for this specific segment.
* **Volume Analysis**: A total of **1.13M units** were sold globally, generating a net profit of **$16.89M**.
