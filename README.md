# Amazon_Vine_Analysis

## Overview of the analysis:
Analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

This project analyzes reviews for sports equipment to see if there is any bias towards favorable Vine members. 

## Resources

- Data Source: [Amazon Review Datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), [Sports Equipment](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Sports_v1_00.tsv.gz)
- Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS
## Results: 

How many Vine reviews and non-Vine reviews were there?
  * There are a total of 334 Vine (paid) reviews and 61614 non-Vine (unpaid) reviews. 

![Screenshot (194)](https://user-images.githubusercontent.com/90067477/150408012-ab96658b-bd8f-4d77-ac34-eae4fea5cd11.png)


How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
 * With a total of 32804 5 star reviews there were 139 5 star Vine reviews and 32665 5 star non-Vine reviews.  
  
  ![Screenshot (196)](https://user-images.githubusercontent.com/90067477/150410410-778c6e8b-130a-4eef-9302-f8cbfeb6e9ac.png)


What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
 * 54% of the Vine reviews were five star, 51% of the non-Vine reviews were five stars. 
![Screenshot (198)](https://user-images.githubusercontent.com/90067477/150410686-afb7b8de-1d83-4875-a40a-6347a30e7465.png)


## Summary: 
With both sets of reviews within 3% of each other in the five star ratings there appears to be no bias between the two sets of reviews. To provide more insight onto this ossible issue I would recommend collecting all ratings of one to five stars to fully see the spread of reviews.    
