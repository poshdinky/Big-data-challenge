## Background

In this assignment, you will put your ETL skills to the test. Many of Amazon's shoppers depend on product reviews to make a purchase. Amazon makes these datasets publicly available. They are quite large and can exceed the capacity of local machines. One dataset alone contains over 1.5 million rows; with over 40 datasets, data analysis can be very demanding on the average local computer. Your first goal for this assignment will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.
This homework assignment contains two levels. The second level is optional but highly recommended.


Create DataFrames to match production-ready tables from two big Amazon customer review datasets.


Analyze whether reviews from Amazon's Vine program are trustworthy.

## Grading
It appears after analyzing the data that there is a small diffrence of 11.4% between the vine reviews (41.61%) and the non-vine ones (53.01%) which represents a slight bias of them in the vine program.
In addition to this analyse we could calculate the mean, median and mode of the dataset for the Vine and non-Vine reviews.

## Grading

* Follow the [Unit 22 Rubric - Big Data Homework - "Alexa, can you handle big data?"](https://docs.google.com/document/d/1H-TBgBUz1jVGG1zvo046GraApmbepVZgYionh-4mNas/edit?usp=sharing) for grading instructions.

## Bug Report

[Having issues with this homework? Report a bug!](https://bit.ly/2RLCefU)
