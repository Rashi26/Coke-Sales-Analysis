# Coca-Cola Sales Analysis — Project Report

## 1. Executive Summary

This project analyzes Coca-Cola sales performance across U.S. retailers, regions, and beverage brands using Microsoft Excel.

The analysis focuses on sales and volume, retailer and regional performance, pricing and profitability, and monthly and seasonal trends.

The goal was to move from transaction-level data to a business-oriented view of performance using Excel tables, formulas, PivotTables, charts, slicers, and an interactive dashboard.

### Overall Performance

| KPI | Result |
|---|---:|
| Total Sales | **$8.68M** |
| Units Sold | **17.15M** |
| Operating Profit | **$3.17M** |
| Overall Operating Margin | **~36.5%** |

> **Core takeaway:** The largest sales contributors are not necessarily the most efficient. The analysis reveals a clear distinction between **scale and profitability efficiency**.

---

## 2. Business Question

### How can Coca-Cola optimize sales and profitability across U.S. retailers and regions?

The analysis investigates:

- Which retailers generate the most revenue and volume?
- Which retailers achieve the strongest margins?
- Which regions drive sales and operating profit?
- Which regions are most efficient?
- Which beverage brands lead in sales and units?
- How does pricing relate to volume?
- How does performance change throughout the year?
- Where are the strongest opportunities for improvement?

---

## 3. Dataset & Analysis Approach

The analysis uses transaction-level Coca-Cola sales data for 2021.

Key fields include:

- Retailer
- Retailer ID
- Invoice Date
- Region
- State
- City
- Beverage Brand
- Price per Unit
- Units Sold
- Total Sales
- Operating Profit
- Operating Margin
- Month

### Analytical workflow

```text
Raw Transaction Data
        ↓
Data Preparation
        ↓
Calculated Metrics
        ↓
PivotTables & Aggregations
        ↓
Exploratory Analysis
        ↓
Charts & Dashboard
        ↓
Business Insights
        ↓
Recommendations
```

---

# 4. Executive Dashboard

![Dashboard](images/dashboard.png)

*Add the final dashboard screenshot above.*

The dashboard provides an executive-level view of:

- Total Sales
- Units Sold
- Operating Profit
- Retailer performance
- Monthly sales trends
- Regional performance
- Brand performance

The overall business generated approximately **$8.68M in sales**, **17.15M units**, and **$3.17M in operating profit**.

---

# 5. Retailer Performance

![Retailer Performance](images/retailer-performance.png)

*Add the retailer analysis screenshot above.*

Retailer performance was evaluated using Total Sales, Units Sold, Operating Profit, and Operating Margin.

| Retailer | Sales | Operating Profit | Margin |
|---|---:|---:|---:|
| **Sodapop** | $4.40M | $1.65M | 37.4% |
| FizzySip | $2.58M | $0.84M | 32.3% |
| BevCo | $1.29M | $0.54M | **42.0%** |
| DreamCo | $0.40M | $0.15M | 36.6% |

### Insight

**Sodapop is the scale leader**, contributing more than half of total sales.

However, **BevCo has the highest operating margin at approximately 42%**.

> **Sodapop represents scale, while BevCo represents efficiency.**

A useful next step would be to investigate what drives BevCo's stronger margin and whether those practices can be replicated across larger retail relationships.

---

# 6. Regional Performance

![Regional Analysis](images/regional-analysis.png)

*Add the regional analysis screenshot above.*

Regional performance was compared across the West, Northeast, Southeast, South, and Midwest.

| Region | Sales | Operating Profit | Margin |
|---|---:|---:|---:|
| **West** | $2.84M | $0.92M | 32.6% |
| Northeast | $1.79M | $0.63M | 35.2% |
| Southeast | $1.62M | $0.64M | 39.6% |
| South | $1.29M | $0.54M | **42.0%** |
| Midwest | $1.15M | $0.44M | 38.0% |

### Insight

The **West is the largest region by sales and total operating profit**, but it has a lower operating margin than several smaller regions.

The **South has the strongest operating margin**, making it a useful benchmark for profitability efficiency.

---

# 7. Brand Performance

![Brand Performance](images/brand-performance.png)

*Add the brand analysis screenshot above.*

The beverage portfolio was analyzed using sales, units, price per unit, and operating margin.

### Key result

**Coca-Cola is the leading brand** in the dataset:

- Sales: **~$2.02M**
- Units Sold: **~4.13M**
- Operating Margin: **~39.4%**

Other brands analyzed include Dasani Water, Diet Coke, Sprite, Powerade, and Fanta.

The analysis highlights that different brands have different combinations of price, volume, and profitability.

---

# 8. Monthly & Seasonal Trends

![Monthly Trends](images/monthly-trends.png)

*Add the monthly trend screenshot above.*

Monthly sales were analyzed to identify seasonal patterns and peak periods.

### Key observations

- **March:** Lowest monthly sales at approximately **$484K**
- **July:** Approximately **$1.04M**
- **December:** Highest monthly sales at approximately **$1.05M**

Sales more than doubled between March and the July peak.

### Insight

The data suggests a strong seasonal pattern, with significant demand during the summer and another major peak in December.

This can support inventory planning, distribution planning, retailer coordination, and seasonal promotions.

---

# 9. Pricing & Volume Analysis

![Price vs Volume](images/price-vs-volume.png)

*Add the pricing analysis screenshot above.*

Price per unit was compared with unit volume across beverage brands.

The purpose is to identify patterns between price positioning and demand.

> The analysis identifies **relationships, not causal effects**.

A more advanced pricing analysis would incorporate competitor pricing, discounts, promotional activity, store/channel information, and customer-level behavior.

---

# 10. Profitability Analysis

Operating profit and operating margin were used alongside sales and units to provide a more complete view of performance.

The overall operating margin is approximately **36.5%**, based on total operating profit divided by total sales.

### Scale vs. efficiency

**Sodapop**
- Largest retailer by sales
- Strong operating profit
- ~37.4% margin

**BevCo**
- Much smaller sales contribution
- ~42.0% operating margin
- Highest retailer margin

The business opportunity is therefore not simply to maximize revenue, but to understand how revenue can be converted into stronger profitability.

---

# 11. Excel Implementation

The project was built using standard Excel analytics functionality.

### Data Preparation

- Structured transaction-level data
- Standardized fields
- Worked with date and numeric fields
- Created month-based analysis
- Organized calculated metrics

### Analysis

- Excel formulas
- PivotTables
- PivotCharts
- Aggregations
- Retailer comparisons
- Regional comparisons
- Brand comparisons
- Monthly trend analysis

### Visualization

- KPI cards
- Bar charts
- Line charts
- Comparative charts
- Conditional formatting
- Interactive slicers
- Dashboard layout

---

# 12. Business Recommendations

## 1. Optimize the largest retailer relationship

Sodapop represents a substantial share of total sales. Improvements in pricing, product mix, inventory availability, promotions, and retail execution could have a meaningful impact.

## 2. Investigate BevCo's margin advantage

BevCo achieves the strongest retailer margin despite being much smaller than Sodapop.

Management should investigate whether this is related to product mix, pricing, promotional strategy, operating costs, or regional characteristics.

## 3. Improve profitability in the West

The West is the largest market by revenue and total profit, but its margin is comparatively lower.

Potential areas for investigation include retailer-specific margins, product mix, pricing, promotional discounts, and operating costs.

## 4. Plan around seasonal peaks

The strong summer and December sales periods suggest an opportunity to align inventory, distribution, marketing, and retailer promotions with expected seasonal demand.

## 5. Use the South as a profitability benchmark

The South has the highest operating margin. Comparing its retailer mix, brand mix, pricing, and operating characteristics with lower-margin regions could help identify opportunities to improve profitability elsewhere.

---

# 13. Limitations

The analysis is primarily descriptive and based on the available sales transaction data.

Factors such as competitor pricing, promotions, advertising spend, store-level characteristics, customer demographics, weather, distribution costs, and inventory levels are not included.

Therefore, the findings should be interpreted as **business insights and areas for investigation**, rather than proof of causal relationships.

---

# 14. Future Enhancements

The project could be extended with:

- Sales forecasting
- Profit forecasting
- Price elasticity analysis
- Competitor pricing
- Promotion effectiveness
- Store-level analysis
- Customer segmentation
- Geographic mapping
- Weather and external demand variables
- Predictive modeling
- Power BI reporting

These additions would move the project from descriptive analytics toward **predictive and prescriptive analytics**.

---

# 15. Conclusion

This project demonstrates how Excel can transform raw sales transactions into a structured business intelligence solution.

The analysis reveals that:

- **Sodapop is the largest retailer by sales**
- **BevCo has the strongest retailer margin**
- **The West is the largest region**
- **The South has the highest regional margin**
- **Coca-Cola leads the beverage portfolio**
- **Sales show strong seasonal peaks**

The most important takeaway is that **sales volume, revenue, and profitability tell different parts of the story**.

By combining these metrics through Excel dashboards and multidimensional analysis, the project provides a more complete view of where Coca-Cola is performing well and where opportunities for improvement may exist.
