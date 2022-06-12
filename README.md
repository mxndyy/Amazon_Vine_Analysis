# Amazon_Vine_Analysis

## Analysis Overview 

The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program which is a service that allows manufacturers and publishers to receive reviews for their products. The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.\
This analysis focuses on reviews for shoes.

## Deliverables:
This assignment consists of two technical analysis deliverables and a written report on the analysis.

1. ***Deliverable 1:*** Perform ETL on Amazon Product Reviews
2. ***Deliverable 2:*** Determine Bias of Vine Reviews
3. ***Deliverable 3:*** Written Report on the Analysis

## Results

### Number of Vine reviews 

![vine_reviews.png](/Results/vine_reviews.png)

### Number of non-Vine reviews

![non_reviews.png](/Results/non_reviews.png)

### Number of 5 Star Vine Reviews 

![vine_5.png](/Results/vine_5.png)

### Number of 5 Star non-Vine Reviews

![non_5.png](/Results/non_5.png)

### Percentage of 5 Star Vine Reviews

![vine_percentage.png](/Results/vine_percentage.png)

### Percentage of 5 Star non-Vine Reviews

![non_percentage.png](/Results/non_percentage.png)

## Summary

59% of the reviews in the Vine program were 5 star reviews. 53% of reviews in non-Vine were 5 star reviews. This describes a slight positivity bias for reviews in the Vine program. Additionally, we could analyze the distribution of all star ratings for the vine and non-vine reviews. 