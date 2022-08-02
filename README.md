# Amazon Vine Analysis
## Overview of the analysis
The purpose of the project is to analyze Amazon reviews by members of the paid Amazon Vine program. There are multiple datasets from the program and the video game review data was analzyed. An ETL process with PySpark was utilized for the analysis: the data was extraced and transformed, connected to an AWS RDS instance, and loaded into pgAdmin. The data was reviewed for any bias based on Vine membership status.
## Results
- There were 94 Vine reviews and 40,471 non-Vine reviews.
- There were 48 5 star Vine reviews and 15,663 5 start non-Vine reviews.
- 51.1% of Vine reviews were 5 star reviews and 38.7% of non-vine reviews were 5 star reviews.
## Summary
