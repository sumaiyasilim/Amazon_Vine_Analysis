# Amazon_Vine_Analysis

## Overview of the analysis of the Vine program

This analysis was done on Amazon reviews written by members of the paid Amazon Vine program and non-members, using the shoes dataset. PySpark was used to determine if there was any bias towards favorable reviews from Vine members in the shoe dataset.

## Results

![paid_vines](https://user-images.githubusercontent.com/64383146/186316032-166e7b26-451b-4384-a431-67210896f60b.png)  ![unpaid_vines](https://user-images.githubusercontent.com/64383146/186316121-2fba63ab-41de-4ccf-8118-27ef0219a093.png)

- There were 22 Vine reviews and 26,987 non-Vine reviews
- There were 13 Vine reviews that were 5 stars and 14,475 non-Vine reviews that were 5 stars
- The percentage of Vine reviews that were 5 stars is 59.09% and for non-Vine reviews it was 53.64%

## Summary

From looking at the data above, it can be concluded that there is no positivity bias for reviews in the Vine program but the dataset for Vine reviews is significantly smaller than the non-Vine reviews, so it would make it difficult to make a solid conclusion. In order to provide a more accurate analysis, a bigger dataset for the Vine reviews is needed.

Additionally, when looking at the percentage of non-Vine 5-star reviews, we can see that this is an impressive number as it compares to the percentage of Vine reviews.
