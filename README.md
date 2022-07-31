# Amazon Vine Program Analysis

## Overview 
- In this project we have been assigned to analyze the reviews written by members and non-members of the Amazon Vine Program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. In the final analysis we will be answering some questions such as if the reviews under the paid Vine Program are biased compared to the reviews written by non-members of the Vine Program.

## Results of the analysis

### SQL Tables lookup
#### Customers Table
![customer_table](/resources/sql_customertable.png)

#### Products Table
![product_table](/resources/sql_producttable.png)

#### Review Table
![review_table](/resources/sql_reviewidtable.png)

#### Vine Table
![vine_table](/resources/sql_vinetable.png)

### Percentage of 5* reviews
#### Vine Program Members
![vine_perc](/resources/paid_percent.png)

#### Non-members
![non_mem](/resources/unpaid_percent.png)

## Summary
### Is there any positivity bias for reviews in the Vine Program?
- From the previews analysis, with 51.06% 5 star rating reviews under the Vine Program compared to 38.7% of 5 star reviews from non-members it is fair to assume these reviews are being positively influenced by the paid Vine Program.

- From the following additional analysis I can strongly support the previews statement about the positivity bias for the reviews. In the following image we can verify that paid reviews with 4 or 5 star ratings reach a stunning 76.6% while reviews from non-members only goes up to 55.35%. To verify the veracity of everything we need to perform an analysis comparing the reviews to the verified purchases.

### ADDITIONAL ANALYSIS
#### Vine Program Members & Non-Members 4* plus percentage comparison
![four_star](/resources/4star_comparison.png)