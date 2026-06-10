# -Sales-Data-Statistical-Analysis-
This project analyzes sales revenue data from January 2025 to April 2025 using Microsoft Excel. The goal is to understand sales performance by examining revenue trends, variability, distribution patterns, outliers, and relationships between key business variables such as price, quantity, and revenue.
# Sales Revenue Analysis using Excel

## Introduction
This project analyzes sales revenue data from January 2025 to April 2025 using Microsoft Excel. The goal is to understand sales performance by examining revenue trends, variability, distribution patterns, outliers, and relationships between key business variables such as price, quantity, and revenue.

The analysis was conducted using descriptive statistics, histogram analysis, correlation analysis, and outlier detection techniques. The findings provide insights into business performance and support data-driven decision-making.

---

## Dataset
The dataset contains 118 sales transactions and includes the following fields:
* **Product**
* **Category**
* **Price**
* **Quantity**
* **Revenue**
* **Region**
* **Date**

---

## Analysis Performed

### 1. Descriptive Statistics
Revenue was analyzed using measures of central tendency.

| Statistic | Value |
| :--- | :--- |
| **Mean Revenue** | 2,655.00 |
| **Median Revenue** | 1,947.50 |
| **Mode Revenue** | 1,650 and 1,680 |
| **Minimum Revenue** | 300 |
| **Maximum Revenue** | 25,000 |

> **Key Finding:** The mean revenue is higher than the median, suggesting that a few large sales transactions are increasing the average revenue.

### 2. Variability Analysis
| Measure | Value |
| :--- | :--- |
| **Variance** | 7,156,549.04 |
| **Standard Deviation** | 2,675.17 |

> **Key Finding:** Revenue values vary considerably across transactions, indicating moderate sales volatility.

### 3. Distribution Analysis
A histogram was created to examine the distribution of revenue values.

**Findings:**
* Most revenue values are concentrated below 4,100.
* The distribution is positively skewed.
* A small number of high-value transactions create a long right tail.
* The data is not normally distributed.

### 4. Outlier Detection
Using the IQR (Interquartile Range) method, several revenue outliers were identified.

| Product | Revenue |
| :--- | :--- |
| Phone | 5,520 |
| Headphones | 6,000 |
| Tablet | 6,900 |
| Phone | 14,000 |
| Laptop | 25,000 |

> **Key Finding:** These transactions are significantly larger than the majority of sales and have a strong impact on the overall average revenue.

### 5. Correlation Analysis

* **Price vs Quantity**
  * **Correlation Coefficient:** -0.538
  * This indicates a moderate negative relationship between price and quantity sold. As prices increase, customers generally purchase fewer units.

* **Quantity vs Revenue**
  * **Correlation Coefficient:** -0.015
  * This indicates a very weak relationship between quantity sold and revenue, suggesting that product pricing plays a major role in determining revenue.

---

## Key Insights
* The typical revenue per transaction is approximately 1,947.50.
* Revenue performance is moderately volatile.
* Several extreme sales transactions significantly influence overall revenue.
* Most sales generate relatively low to moderate revenue.
* Higher prices tend to reduce sales quantity.
* Quantity alone is not a strong predictor of revenue.

---

## Recommendations

* **Focus on High-Revenue Products** Products such as Laptops and Phones contribute the most to total revenue and should receive greater business attention.
* **Investigate Exceptional Sales** Analyze the factors behind high-revenue transactions to determine whether they can be replicated through marketing campaigns or promotional activities.
* **Optimize Pricing** Maintain competitive pricing strategies to avoid reducing customer demand while maximizing profitability.
* **Improve Revenue Consistency** Implement loyalty programs, targeted promotions, and customer retention strategies to generate more stable revenue over time.

---

## Conclusion
The analysis revealed that the business generates most of its revenue from a relatively small number of high-value transactions. Revenue distribution is positively skewed due to several outliers, while overall sales performance shows moderate variability. 

By focusing on high-performing products, understanding exceptional sales events, and optimizing pricing strategies, the business can improve both revenue growth and stability.

---

## Tools Used
* Microsoft Excel
* Descriptive Statistics
* Histogram Analysis
* Correlation Analysis
* IQR Outlier Detection
* Data Visualization
