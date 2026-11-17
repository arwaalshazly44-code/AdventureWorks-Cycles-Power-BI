# AdventureWorks-Cycles-Power-BI
# AdventureWorks Cycles – Power BI Analysis

## Project Overview

This project analyzes AdventureWorks Cycles' sales, products, customers, and returns data using Power BI.

The goal is to explore business performance, identify trends and patterns, and turn raw data into meaningful business insights that can support better decision-making.

## Dashboard Pages

The report consists of eight interactive pages:

| Page | Description |
|---|---|
| Home | Main navigation page providing access to different analysis sections. |
| Sales | Overview of revenue, profit, orders, and sales performance across time and countries. |
| Revenue Details | Drill-down analysis of revenue by year, region, category, subcategory, product, and customer. |
| Products | Analysis of product performance, quantity sold, revenue, and profit. |
| Customer | Overview of customer contribution and purchasing behavior. |
| Customer Details | Detailed customer-level analysis. |
| Returns | Overview of returned products, return orders, and lost sales. |
| Returns Details | Detailed analysis of returns and their financial impact by product. |

## Key Business Findings & Insights

### 1. Sales Performance

**Revenue Trends**
- 2020 revenue reached approximately 6.4M.
- 2021 revenue reached approximately 9.32M.
- 2022 revenue reached approximately 9.18M.

**Insight:** Revenue in 2022 was slightly lower than in 2021. However, 2022 contains only six months of data, so a direct comparison between the two years may be misleading.

**Profitability**
- June 2022 recorded the highest monthly profit during the first six months of the year, reaching approximately 771.6K.
- This performance was supported by increases in both revenue and profit margin compared with the other months in the same period.

**Insight:** Analyzing both revenue and profit margin provides a better understanding of what drives profitability.

**Sales by Category**
- Bikes generated the highest revenue and profit.
- Accessories recorded the highest sales volume, with 58K units (68.68% of total quantity sold).
- Despite its higher sales volume, Accessories contributed less profit than Bikes.

**Insight:** High sales volume does not necessarily translate into higher profitability.

**Sales by Country**
- The United States led in revenue, profit, and order volume.
- Australia recorded the highest average order value.

**Insight:** The United States is the strongest market in overall sales contribution, while Australia has a higher average spend per order.

**Workday vs. Weekend Orders**
- Workdays accounted for 71.77% of orders.
- Weekends accounted for 28.23% of orders.
- After considering the number of days in each group (5 workdays and 2 weekend days), the average daily order share was nearly equal.

**Insight:** Although most orders occur during workdays, weekend activity is relatively strong when adjusted for the number of days.

### 2. Revenue Analysis

The Decomposition Tree was used to explore revenue through multiple levels, including year, region, category, subcategory, product, and customer.

**Top Revenue-Contributing Customers**
- 2020: Rafael Xu
- 2021: Janet Munoz
- 2022: Franklin Xu
- Overall: Jordan Turner

**Insight:** The leading customer changes across individual years, while Jordan Turner contributes the highest revenue across the full analyzed period.

### 3. Product Performance

**Revenue and Profit**
- Mountain-200 Black, 46 was the top-performing product in both revenue and profit.

**Orders and Quantity**
- Water Bottle – 30 oz. was among the leading products in both order volume and quantity sold.

**Lost Sales**
- Sport-100 Helmet Red recorded the highest lost sales among the analyzed products.

**Insight:** Product performance differs depending on the metric. A product that drives high order volume may not necessarily generate the highest revenue or profit.

### 4. Returns Analysis

**Key Return Metrics**
- Return Quantity: 1,828
- Return Orders: 1,809
- Lost Sales: 765K
- Returned Products: 124

**Product-Level Findings**
- Water Bottle – 30 oz. recorded the highest return quantity.
- Sport-100 Helmet Red recorded the highest lost sales.

**Return Trends**
- Return quantity increased from 2020 to 2022.
- Lost sales also increased over the same period.
- 2022 recorded the highest return quantity, return orders, and lost sales.

**Insight:** The upward trends in return volume and lost sales indicate a potential issue that requires further investigation. Identifying the products contributing most to returns can help prioritize improvement efforts.

## Data Limitations

- The 2022 dataset covers only six months.
- Therefore, yearly comparisons involving 2022 should be interpreted carefully.
- Return quantities should also be compared against total orders or sales to determine whether the return rate itself is increasing.

## Tools & Skills

- **Power BI:** Interactive dashboard development and data visualization.
- **Power Query:** Data cleaning and transformation.
- **DAX:** Measures and business calculations.
- **Data Modeling:** Organizing data to support analysis and reporting.
- **Business Analysis:** Identifying trends, evaluating performance, and extracting business insights.

## Project Screenshots

Screenshots of the dashboard will be added here.

## Conclusion

This project demonstrates how Power BI can be used not only to visualize business data, but also to investigate performance, identify meaningful patterns, and generate insights that can guide further business analysis.
