
## EXPLORATORY DATA ANALYSIS OF SUPERSTORE SALES DATA 
![Picture1](https://github.com/Motade/Superstore_Sales_Analysis/assets/114887240/ac5aa374-7884-4023-8b27-39c94f89ee43)

## PROJECT OBJECTIVE
My aim in this project is to conduct a comprehensive sales analysis that will enable me to optimize profitability and regional performance for our product categories. To achieve this goal, I will:
- Calculate and total sales and profit by product category, and identify the most and least profitable product categories.
- Investigate consistent loss-generating categories.
- Analyze regional sales data to find top and bottom-performing regions.
- Utilize the insights gained to make strategic decisions regarding:
  - Product categories
  - Regions
  
## DATA CLEANING PROCESS
1. **Dropped Columns:** In the initial phase, I removed the "row id" and "customer id" columns as they were unnecessary for our analysis. Additionally, I dropped the "country" column since all stores are located in the USA.

2. **Duplicate Check:** I conducted a check for duplicate records, and fortunately, no duplicates were found in the dataset.

3. **Creating New Columns:** During data inspection, I identified that the "profit" column contained both profits and losses. To prevent any confusion in our analysis, I introduced two new columns: one for profit and another for loss. I also renamed the original "profit" column to "profit and loss" to better reflect its content and purpose.

Profit : *=IF([@[Profit and Loss]]>0,[@[Profit and Loss]],0)*`

Loss : *=IF([@[Profit and Loss]]<0,[@[Profit and Loss]],0)*`

### RESULTS AND FINDINGS
1. Total revenue and profit by product category: Examining revenue and profit by product category reveals that the technology category stands out, generating the highest revenue of $836,154.03, contributing to a substantial 41.59% of the company's profit. It is closely trailed by the office supplies category, with a revenue of $719,047.03, making up 40.47% of the company's profit. In contrast, the furniture category, although generating revenue of $741,718.42, accounts for approximately $79,387.38, representing 17.94% of the company's total profit.

 ![image](https://github.com/Motade/Superstore_Sales_Analysis/assets/114887240/09187ab9-15dc-47d5-8a09-bdda60d364e9)

 2. Loss-Generating Categories: The furniture category incurred a loss of $60,294.05. It's important to highlight that this category not only experienced a significant loss but also generated the lowest profit among all categories

![image](https://github.com/Motade/Superstore_Sales_Analysis/assets/114887240/400c4ed2-90aa-4779-97ec-d4bfbcc17190)

3.Top and Bottom-Performing Regions: In terms of revenue generation, the West region led with $725,457.82, followed by the East with $678,499.87. The Central region contributed $501,239.89, while the South region generated the least revenue, totaling $391,721.91

![image](https://github.com/Motade/Superstore_Sales_Analysis/assets/114887240/4a455da0-fcf4-41f4-86a1-16bdff8bbacd)

### RECOMMENDATIONS
Based on the insights, I recommend the following strategic actions to optimize profitability and market presence:

1. It is crucial to address the Furniture category, which incurred a significant loss and contributed the lowest profit. A thorough review of its product lineup, pricing strategies, and cost-saving measures is necessary.

2. The Technology and Office Supplies categories, which are strong revenue contributors, should  be explored for opportunities by diversificating and investing in robust marketing campaigns.

3. The West region's leading revenue generation should be sustained through continuous market monitoring and increased resource allocation. In contrast, the South region, with the lowest revenue, requires an analysis of local market conditions, customization of offerings, and potential partnerships or promotions for growth.


To interact with the dash board [click here](https://motray-my.sharepoint.com/:x:/g/personal/motray_motray_onmicrosoft_com/EQKJXJCdIaRKsFHubvaxdIUBViDIHNV3Tv-Ts4vFfcARow?e=1yjgmn&nav=MTVfezlENzlFQTQ0LTI0RjUtNERCQy04RjU4LTgwQjdBN0E1RUM3OX0)


Yours sincerely,

Motunrayo Oguntade.
