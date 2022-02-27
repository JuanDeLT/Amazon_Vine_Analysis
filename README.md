# Amazon_Vine_Analysis

## Overview of Project

This project is meant to determine Amazon review bias for Vine reviewers using pyspark and AWS S3 resources to store, extract, and manipulate data.

## Results

- How many Vine reviews and non-Vine reviews were there?
    - The total number of paid reviews is: 60.
    - The total number of unpaid reviews is: 14477.
    - The total number of reviews is: 14537.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    - The total number of 5 star paid reviews is: 34.
    - The total number of 5 star unpaid reviews is: 8212.
    - The total number of 5 star reviews is: 8246.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    - The percentage of 5-star reviews for paid reviews is: 0.5666666666666667%.
    - The percentage of 5-star reviews for unpaid reviews is: 0.5672445948746287%.

## Summary of Statistical Analysis
Based on the percentage of Vine and non-Vine reviews that were 5 stars, there seems to be no positivity bias for reviews in the Vine Program for musical instruments. That being said, a very small proportion of the total reviews were from Vine reviews, less than 1% of them in fact. Another analysis that would be interesting to see would be to determine how many 1-star reviews are found in each category.



