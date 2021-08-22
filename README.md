# Amazon_Vine_Analysis

# Project Overview:

Request from client to analyze Amazon Vine program; Determine bias toward favorable reviews from Vine members.

*What is Amazon Vine?
Amazon Vine is a program launched by Amazon.com that allows manufacturers and publishers to receive reviews for their products from a filtered group of Amazon customers, called "Vine Voices." These Vine Voices are chosen based on several criteria, including their total number of reviews and helpfulness of reviews. In exchange for free products, these Vine Voices are required to publish a review. Amazon's Vine help guide states that "Voices are not paid" and that Amazon welcomes an "honest opinion about the product."*

## Proceedor 

* Uses PySpark to perform ETL process to extract the dataset,
* Transform the data, 
* Connect to an AWS RDS instance, 
* Load the transformed data into pgAdmin and calculate different metrics
*US Reviews for Video Games*

## Resources 

!(Data source in zip file avaliable above.) Title: Amazon Review Datasets, Video Games Review Dataset 
!Jypter Notebook
!PostgreSQL 
!pgAdmin 4
!AWS

## Results

!Based on this analysis, there appears to be a positivity bias among Video Game reviews in the Vine program.! 

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.

For the Video Game dataset:

* There are only 94 Vine reviews.
* 48 of Vine reviews gave 5-stars.
* 51.06% of Vine reviews were 5-stars.
* There are 40,471 non-Vine reviews.
* 15,663 non-Vine reviews gave 5-stars.
* Approximately 38.70% of non-Vine reviews were 5-stars.

*(It should be noted that the data present in this dataset is not reflective of a single product. This dataset contains a multitude of different hardware, software and accessories for different video game consoles. As a result of this large variety of products, this analysis cannot be applied to individual products, but rather the dataset as a whole.)*

## Suggestions

1. Analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

2. Further research the possibility of positivity bias is to compare the average Vine review ratings to the average customer rating. If it is found that Vine customers have a higher average star rating than non-Vine customers, this might be an indication of positivity bias.
