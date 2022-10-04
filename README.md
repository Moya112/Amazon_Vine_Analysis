# Amazon_Vine_Analysis
Module 16: Big Data

# Project Overview
Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who must publish a review. In this project, we have access to approximately 50 datasets. Each contains reviews of a specific product, from clothing apparel to wireless products. Upon selecting a dataset, we use PySpark to perform the ETL process, extract the data, transform it, connect it to an AWS RDS instance, and load the transformed data into pgAdmin. Next, PySpark, Pandas, or SQLis use to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

# Resources
- Data: Amazon Review datasets
- Software and tools: Python PySpark and Pandas, AWS RDS and S3 services, SQL and pgAdmin

# Results
<img width="1107" alt="Screen Shot 2022-10-04 at 12 41 17 PM" src="https://user-images.githubusercontent.com/105765150/193885324-4c714e6c-7c33-4532-bbb3-b42b56ef367e.png">

# Summary
The data analysis showed that 52% of the reviews in the Vine program were five stars reviews out of 21 total reviews, whereas the percentage in the non-Vine program reviews is 57% out of 7689 reviews. Ratios reveal a positivity bias for studies in the Vine program. Additionally, we could analyze the one-way ANOVA test for 5-star ratings for the Vine and non-Vine reviews to see whether or not the percentage of difference is statistically significant.
