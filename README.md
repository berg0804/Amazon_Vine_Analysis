# Amazon Vine Analysis
## Overview of the Analysis
The purpose of the project is to analyze Amazon reviews by members of the paid Amazon Vine program. There are multiple datasets from the program and the video game review data was analzyed. An ETL process with PySpark was utilized for the analysis: the data was extraced and transformed, connected to an AWS RDS instance, and loaded into pgAdmin. The data was reviewed for any bias based on Vine membership status.
## Results
- There were 94 Vine reviews and 40,471 non-Vine reviews.
![image](https://user-images.githubusercontent.com/67160240/182483766-209ab2e9-5f4a-469a-992b-f4a8441b6fdd.png)
- There were 48 5 star Vine reviews and 15,663 5 star non-Vine reviews.
![image](https://user-images.githubusercontent.com/67160240/182483852-b19416dd-c8f5-4770-a6d8-cf7f3841d7bc.png)
- 51.1% of Vine reviews were 5 star reviews and 38.7% of non-vine reviews were 5 star reviews.
![image](https://user-images.githubusercontent.com/67160240/182483898-41fe891e-2f3b-4af0-b05c-b0ea3b6761b1.png)
## Summary
According to the analysis of video game reviews, members of the Amazon Vine program had a higher perecentage of 5 star reviews. Vine members had a 32% higher rate of 5 star reviews (51.1% vs. 38.7%). An additional analysis that can be completed is the type of reviews left by each customer. It will be helpful to know each customer's review history to see if the customer is more prone to positive or negative reviews.
