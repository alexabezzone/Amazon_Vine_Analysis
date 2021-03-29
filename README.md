# Amazon_Vine_Analysis

## Overview

After working on a successful big data project at BigMarket, the team assigned you with another large project to analyze Amazon reviews written by members of the paid Amazon Vine program. The program is a paid service where Amazon reviewers write paid reviews for items and services. The assignment is to choose one dataset out of 50 products and services to use PySpark to conduct the ETL process to extract the dataset, transform the data, connect to an AWS RDS, and load the data into pgAdmin. The chosen dataset for this assignment is book reviews. The purpose of this study is to conduct the ETL proccess to analyze Amazon Vine reviews for books on the Amazon platform. 

## Results

1. How many Vine reviews and non-Vine reviews were there? 
<img width="1106" alt="Screen Shot 2021-03-28 at 2 02 18 PM" src="https://user-images.githubusercontent.com/74932178/112762583-58284080-8fce-11eb-9edd-95009fc8937c.png">

- There were 0 paid Vine reviews for books on Amazon. 
- There were 496,450 unpaid reviews for books on Amazon. 

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
<img width="1106" alt="Screen Shot 2021-03-28 at 2 04 50 PM" src="https://user-images.githubusercontent.com/74932178/112762615-945ba100-8fce-11eb-90a3-54c6c353f004.png">

- There were 0 paid Vine reviews that were 5 stars.
- There were 257,255 unpaid reviews that were 5 stars. 

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
<img width="1103" alt="Screen Shot 2021-03-28 at 2 05 19 PM" src="https://user-images.githubusercontent.com/74932178/112762623-a2a9bd00-8fce-11eb-8851-62e9bfe83df1.png">

- 0% of paid Vine reviews were 5 stars.
- 51.82% of unpaid reviews were 5 stars. 

## Summary
The results of the analysis display that the Amazon Vine program does not write paid reviews for books. Instead, books on Amazon receive a large amount of unpaid reviews from customers. The reason as to why the Amazon Vine program may not need to write reviews for books is because of the community of book consumers. Often after a person reads a book, they feel compelled to share their opinion and provide a review more so than an ordinary product. There could still be, however, a potential positivity bias in how the Amazon Vine program does not leave paid reviews for books. Amazon Vine could have a bias to assume that every book within the Amazon collection will generate thousands of reviews and not conduct paid reviews on that notion. My suggestion for further analysis that could prevent the positivity bias is to investigate what kind of reviews the book consumers are posting to determine if they are negative or positive. With that knowledge, Amazon Vine reviewers should post paid reviews for books to ensure a high volume of positive reviews for each book.
