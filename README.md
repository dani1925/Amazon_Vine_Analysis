# Amazon Reviews ETL
## Big Data

This repository contains an analysis of reviews on software hosted on amazon.

Big data analysis is done using google colab and pyspark, and the results are stored in tables in a database built on AWS.

## Results

The data set contains user information and the reviews they have made about a specific product. one of the columns records whether the user is an Amazon Vine member or not.

The analysis is carried out on the reviews made by vine users and normal users.

In order to have a better idea about the information that the data shows, the data was filtered so that the relationship between useful_votes and total_votes is greater than 50%.


Once the data is filtered, 2 data frames are created to separate Vine users and those who are not.

As expected, the total number of votes from vine users is significantly lower since it is expected that there will be fewer users.

However, an interesting fact is that 41% of the reviews are 5 stars for vine users while the result was 30% for non-vine users.
