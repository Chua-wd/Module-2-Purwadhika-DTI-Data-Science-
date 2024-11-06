**BACKGROUND**

Amazon Web Services (AWS) is a comprehensive and widely adopted cloud platform that offers a variety of infrastructure and application services. As part of its offerings, AWS provides Software-as-a-Service (SaaS) solutions designed to help businesses develop their products in a scalable and efficient manner. AWS SaaS is a developed product that allows organizations to deploy applications quickly, enhance operational efficiency, and foster innovation, making it suitable for startups and large enterprises alike​.

The AWS SaaS approach promotes agility by providing tools and best practices that assist companies in building, migrating, and modernizing their applications on the cloud. This flexibility enables organizations to address customer challenges effectively while ensuring security and compliance across different industries. By leveraging the AWS Marketplace, companies can further expand their reach and revenue, highlighting the potential for significant growth in the SaaS market​.

For more details, you can explore the AWS SaaS resources:
https://aws.amazon.com/saas/

**PROBLEM STATEMENT & OBJECTIVE**

As global demand for cloud-based solutions grows, competition among SaaS providers intensifies, revealing significant profit differences across regions. While the SaaS industry is expanding, the Asia-Pacific and Japan (APJ) region faces unique challenges that limit its profit margins. Companies in APJ often struggle to achieve the same levels of profitability as their counterparts in the America (AMER) and Europe, the Middle East and Africa (EMEA) regions. This situation raises important questions about the factors affecting sales performance in APJ and underscores the need for focused analysis to identify areas for improvement.

Based on sales data from 2020 to 2023, the APJ region's profit margin (3%) lags significantly behind AMER (15%) and EMEA (14%). This analysis aims to investigate the key factors affecting sales performance in APJ to identify drivers of low profitability and recommend strategies for improvement.

Here are the use cases that will be examined:
1. Sales Performance Analysis: Provide summary of sales performance and profitability in the APJ region compared to AMER and EMEA.
2. Correlation Analysis: Exploring the Relationship Between Discounts, Quantity, Sales Volume, and Profit in APJ to determine if discounting strategies are reducing profit margins.

**[Problem Statement]**

As a data analyst, we will attempt to answer the following:
- What specific strategies can be implemented to increase the profitability of the APJ region from 3% to 12% within the next 3 years?

**Data Understanding**

The data provides informationAWS SaaS Sales and consists of 19 columns, which include:
1. Row ID: A unique identifier for each transaction.
2. Order ID: A unique identifier for each order.
3. Order Date: The date when the order was placed.
4. Date Key: A numerical representation of the order date (YYYYMMDD).
5. Contact Name: The name of the person who placed the order.
6. Country: The country where the order was placed.
7. City: The city where the order was placed.
8. Region: The region where the order was placed.
9. Subregion: The subregion where the order was placed.
10. Customer: The name of the company that placed the order.
11. Customer ID: A unique identifier for each customer.
12. Industry: The industry the customer belongs to.
13. Segment: The customer segment (SMB, Strategic, Enterprise, etc.).
14. Product: The product was ordered.
15. License: The license key for the product.
16. Sales: The total sales amount for the transaction.
17. Quantity: The total number of items in the transaction.
18. Discount: The discount applied to the transaction.
19. Profit: The profit from the transaction.

**SUMMARY & RECOMMENDATION**

Summaries:
- Compared to AMER and EMEA, APJ has the lowest total sales, average transaction size, and profit margin, while having the highest average discount.For profit margin, only APJ has an overall negative value.
- In the APJ region, every market segment and industry shows a negative value.
- Japan and Australia have negative profit margins (all negative profit margins come from Japan and Australia — the top 22 by city and country) due to higher discounts (the top 23 discounts by city and country are dominated by Japan and Australia).
- The product data shows that higher discounts are linked to lower profit margins, sometimes causing losses (negative value).
- There is a strong negative correlation between discount and profit (-0.74), indicating that higher discounts significantly reduce profits.
- Sales show a weak negative correlation with discount (-0.21), possibly due to either high discounts leading to lower sales or increased sales of lower-margin products.
- Quantity has weak positive correlations with both sales (0.31) and profit (0.1), suggesting that as quantity increases, sales and profit experience slight gains.
- "High" discounts (above 20%) start to negatively affect profitability.

Recommendations:
1) Setting a cap to reduce High Discounts: 
- consider setting a cap on discounts at or below 20% in order to prevent negative profit margin and boost profitability.

2) Adjust Discount Strategies by Product: 
Try lowering discounts on low-margin products and offering moderate discounts on higher-margin products especially in APJ region.
- set discount below 10% for OneView, ContactMatcher, SaaS Connector Pack, Marketing suite due to negative profitability in the previous performance.
- set discount 20-25% for product with high profit margin, but low sales to boost sales, for example support and storage.

3) Set Strategies for Japan and Australia: 
These two markets drive the highest discounts and correlate with the highest negative profit margins.
- keep the discount below 20% cap to prevent negative profit margin.

4) Encourage Bulk Purchase / increase sales volume: 
Given the weak positive correlation between quantity and both sales and profit, consider offering promotions for larger orders or high quantities with reasonable discounts.

5) Monitor Sales Impact of Discounts: Since sales show a weak negative correlation with high discounts
- test smaller discounts or time-limited offers to boost sales.
