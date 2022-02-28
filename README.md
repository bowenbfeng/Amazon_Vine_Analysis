# Amazon Vine Analysis

## Overview of the analysis of the Vine program

This project aims to analyze Amazon review of video games by using PySpark to perform the ETL process- extracting, transforming, and loading to the database in AWS. The purpose of this project is to evaluate whether there is a favourable review bias from the Vine members of the data set. 

Source: [https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)

## Results

### How many Vine reviews and non-Vine reviews were there?

There are a total of 94 Vine reviews and 40,471 non-Vine reviews. 

![](/Resources/vine1.png)

![](/Resources/vine2.png)

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There are 48 Vine reviews that were 5 stars. There are 15,663 non-Vine reviews that were 5 stars. 

![](/Resources/vine3.png)

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

In total, 38.73% of the reviews were 5 stars. 51.06% of the Vine reviews were 5 stars. 38.70% of the non-Vine reviews were 5 stars. 

![](/Resources/vine4.png)

## Summary

Based on the analysis, it is obvious that the Vine reviews are biased as 51.06% Vine reviews were 5 stars, which is much higher than the average 38.73% or the non-Vine review 38.70% of 5 stars. 

However, this result might also be biased as there are only 94 Vine reviews but there are 40,471 non-Vine reviews. The huge difference in the sample size may also have resulted in this huge difference in 5-star percentages. 
