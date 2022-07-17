# Amazon_Vine_Analysis

# Overview of the analysis

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

Out of a list of 50 different datasets, the Outdoor Reviews was the one chosen for this analysis, where the goal is to determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.


# Resources

Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS


# Results/Deliverables

### •	How many Vine reviews and non-Vine reviews were there?

Total number of reviews paid and unpaid.

•	37544


![image](https://user-images.githubusercontent.com/96086671/179423021-da0abe8d-0bc1-434d-86d0-4140a6f2c806.png)


Vine Reviews.

•	103


![image](https://user-images.githubusercontent.com/96086671/179423063-d1c80cf7-3776-444e-a246-e1309d4842ba.png)

 
Non-Vine reviews.

•	37441


![image](https://user-images.githubusercontent.com/96086671/179423081-92d92fde-4ed4-48cf-bfbe-74bc75235ae2.png)

 
### •	How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Total number of 5-Star Vine Reviews.

•	55
 

![image](https://user-images.githubusercontent.com/96086671/179423117-005c1feb-3dc6-4148-8258-2f6f4339ce1f.png)


Total number of 5-Star Non-Vine Reviews.

•	19736


![image](https://user-images.githubusercontent.com/96086671/179423134-dcf4b0fd-325d-41ba-841c-eb105385fe41.png)

 
### •	What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

Percentage of 5-Star Vine Reviews.

•	53.4%
 

![image](https://user-images.githubusercontent.com/96086671/179423157-1635f6e2-b6e6-4510-a594-209317f39600.png)


Percentage of 5-Star Non-Vine Reviews.

•	52.71%
 
 
 ![image](https://user-images.githubusercontent.com/96086671/179423184-40b91349-2075-4bca-830f-c927a5c27af1.png)

 
# Summary
 
 
 ![image](https://user-images.githubusercontent.com/96086671/179423209-3ca52cd4-5ecf-46aa-942b-2b90802d8b24.png)

 
 
The Dataframe above displays total number of 5-Star reviews, percentage of 5-star unpaid reviews i.e., unpaid 5-star reviews divided by total amount of unpaid reviews, and percentage of paid reviews i.e., paid 5-star reviews divided by total amount of paid reviews.

Analyzing the results, percentages for both paid and unpaid reviews are very close with 53.4% and 52.71% respectively. There could be some bias in paid reviews with a percentage of 53.4% which seems a bit high, but by comparison with unpaid reviews figure of 52.71% gives a very close range suggesting that vine results may be true.

Additionally, the total amount of reviews is 37544 and the amount of paid reviews is 103,this range is too wide indicating that the proportion of reviews is unbalanced.

