### PROJECT OBJECTIVE
My aim in this project is to conduct a comprehensive sales analysis that will enable me to optimize profitability and regional performance for our product categories. To achieve this goal, I will:
- Calculate and total sales and profit by product category, and identify the most and least profitable product categories.
- Investigate consistent loss-generating categories.
- Analyze regional sales data to find top and bottom-performing regions.
- Assess the impact of discounts on profitability.
- Utilize the insights gained to make strategic decisions regarding:
  - Product categories
  - Regions
  - Discount strategies
### **Data Cleaning Process**
1. **Dropped Columns:** In the initial phase, I removed the "row id" and "customer id" columns as they were unnecessary for our analysis. Additionally, I dropped the "country" column since all stores are located in the USA.

2. **Duplicate Check:** I conducted a check for duplicate records, and fortunately, no duplicates were found in the dataset.

3. **Creating New Columns:** During data inspection, I identified that the "profit" column contained both profits and losses. To prevent any confusion in our analysis, I introduced two new columns: one for profit and another for loss. I also renamed the original "profit" column to "profit and loss" to better reflect its content and purpose.

Profit : *=IF([@[Profit and Loss]]>0,[@[Profit and Loss]],0)*`

Loss : *=IF([@[Profit and Loss]]<0,[@[Profit and Loss]],0)*`



![image](https://github.com/Motade/Superstore_Sales_Analysis/assets/114887240/00c22f23-2cb1-4328-90d5-f2c85f801640)

### RESULT AND FINDINGS
1. Total revenue and profit by product category revealed that the customer category led with the highest revenue of $1,161,401.34, contributing to 49.5% of the company's profit. Corporate followed closely with $706,146.37 in revenue, while the home office category generated $429,371.78.

![image](https://github.com/Motade/Superstore_Sales_Analysis/assets/114887240/4a1d2710-0dbb-4cdd-bbbc-03f3fc995224)







