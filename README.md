# Amazon_Vine_Analysis

## Analysis Overview

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.

## Resources

Data Source: Amazon Review datasets, Video Games Review dataset
Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

## Results

### Total number of reviews

![image](https://user-images.githubusercontent.com/82549869/129494890-0d7d1bea-3675-48d6-b571-ed2d9bdd82ed.png)

![image](https://user-images.githubusercontent.com/82549869/129494902-489da8db-a9fc-46f7-ac25-ab56ce7e07ee.png)

### Percentage of 5-star reviews

![image](https://user-images.githubusercontent.com/82549869/129494919-823e73ed-81bf-4fbe-a9fa-c08dbb5595e2.png)

![image](https://user-images.githubusercontent.com/82549869/129494935-1a72bafc-4538-45d4-ae31-67961ecc2a27.png)

## Summary

In the Vine programme, 51% of the reviews were 5 stars, compared to only 39% in non-Vine reviews. In the Vine programme, this describes an optimism bias for reviews.

We might also look at the statistical distribution of the star rating for Vine and non-Vine reviews (mean, median, and mode).
