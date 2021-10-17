# Amazon_Vine_Analysis
## Overview
The objective of this project is to use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. The dataset selected for this project is furniture products. Next, we will determine if there is any bias toward favorable reviews from Vine members (a service that allows manufacturers and publishers to receive reviews for their products) in the dataset.
## Results
- How many Vine reviews and non-Vine reviews were there?  
There are a total of 136 Vine reviews and 18,019 non-Vine reviews.  
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?  
74 of Vine reviews received 5-stars. In addition, 8,482 of non-Vine reviews received 5-stars.  
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?  
54.4 % of Vine reviews and 47.1 % of non-Vine reviews were 5-stars.  

## Summary
In summary, it can be seen that the percentage of vine reviews that received 5 stars were slightly more than non-Vine reviews (54.4% vs 47.1%). So it can be concluded that in the vine program there is a slight positivity bias.  
One additional analysis could have been filtering ``["verified_purchase"]=="Y"`` to only study those who had made verified purchases. 
