# Amazon_Vine_Analysis

## Overview

We will be analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project we have selected a database for Pet Products to analyze. We will use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 
Next, we’ll use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset. 

## Results

We are trying to answer these questions from the database for the Pet Product Reviews:

### How many Vine reviews and non-Vine reviews were there?

Vine reviews: 37,840

<img width="404" alt="Screen Shot 2022-11-12 at 3 21 31 PM" src="https://user-images.githubusercontent.com/107590196/201493155-dfd8f3ff-72ce-44b7-be91-822b99c1b347.png">

Non-Vine reviews: 170

<img width="404" alt="Screen Shot 2022-11-12 at 3 21 21 PM" src="https://user-images.githubusercontent.com/107590196/201493122-f3106f93-900d-4460-aba0-6fdd4a6582de.png">



### How many Vine reviews were 5 stars? 


<img width="684" alt="Screen Shot 2022-11-12 at 3 21 52 PM" src="https://user-images.githubusercontent.com/107590196/201493104-a4f291c3-6dbb-411c-8895-0b1485ad6149.png">

### How many non-Vine reviews were 5 stars?


<img width="734" alt="Screen Shot 2022-11-12 at 3 21 59 PM" src="https://user-images.githubusercontent.com/107590196/201493102-06246b79-134a-4b8b-9c50-f752d10a51b6.png">



### What percentage of Vine reviews were 5 stars? 

38% of the paid reviews were 5 stars

<img width="722" alt="Screen Shot 2022-11-12 at 3 18 00 PM" src="https://user-images.githubusercontent.com/107590196/201492958-6ef05796-bc71-498b-ba00-99db7b7c2667.png">

### What percentage of non-Vine reviews were 5 stars?

54.5% of the reviews were over 5 stars

<img width="761" alt="Screen Shot 2022-11-12 at 3 18 06 PM" src="https://user-images.githubusercontent.com/107590196/201492953-3c968571-51a5-4b39-baa1-432162ec1569.png">


