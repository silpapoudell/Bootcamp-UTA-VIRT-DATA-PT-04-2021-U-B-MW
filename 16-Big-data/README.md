# Big Data

# Module 16  Assignment 


## Overview of the analysis:

The purpose of this analysis is to extract, transform and load the Amazon review dataset from a S3 bucket in an RDS database to a pandas file where we can perform analyses on a table of interest, which has been exported as a csv from Postgres SQL.
The dataset choose to analyze is reviews of beauty products available on Amazon.
Once we extracted the valuable data from the original dataset, our purpose is to discern if there is any bias towards favourable reviews from Vine members in our dataset.


## Results:

To be considered for this dataset, the total votes must greater or equal to 20, and helpful_votes/total_votes are 50% or higher.



The total number of reviews that are eligible for this analysis is 74,760.



For Total Five Star reviews

The total number of 5 star reviews in the complete dataset are 43,446.


**How many Vine reviews and non-Vine reviews were there?

- Total Vine Reviews:

The total number of reviews that have a vine membership is quite small(647) compared to the total sample, as it is only 0.86% of the total number of reviews.

- Total Non-Vine Reviews:

The remaining reviews are made by non-vine users, which come up to 74,113 reviews.



**How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- Total Vine Five Star Reviews: 

The total number of reviews for vine users is 647. The number of five star reviews of that subset is 229.

- Total Non-Vine Five Star Reviews:

The total number of five star reviews from non-vine users is 43,217 out of the 74,113 total reviews.


**What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

The percentage of five star reviews out of the total vine users reviews subset is 35.39%.

The number of five star(non-vine) reviews is 58.31% of the total non-vine user reviews.

Other percentages of note are the percentage of vine five star reviews to total five star reviews. The vine five star reviews make up 0.53% of the total of all five star reviews, where as the non vine five star reviews make up the remaining 99.47%.

Now, the total number of vine user five star reviews out of the total number of reviews is 0.31%, versus the non-vine five star reviews making up 57.81% of the total reviews.


## Summary:

Based on our current dataset, positive bias doesn't appear to be present in the Vine program. 
The percentage of vine reviewer's who give a five star review of the product is 35.39%. 
This is compared to the percentage of five star reviews given by non vine reviewers, which is 58.31%. 
From this data, we can extrapolate that there is no positivity bias and that Vine reviewers seem to be more likely to give a non-positive review to a product than non-vine users.


Perform on this data set would be to establish the measures of central tendency (mean, median, mode) on the star_rating variable. 
This would be useful to see if the data is skewed either way. 
We could then see what the average star ratings were for Vine and non-vine reviewers.







