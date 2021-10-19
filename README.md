## Overview:

- In this, we gathered data on pet product evaluations and used Pyspark to do the ETL process of extracting, converting, and linking the data to a database we built on the AWS server. After that, we ran some tests to see whether there was any evidence of a positive review bias among Vine members in our data set.

## Resources

**Data Source:** https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt

**Software:** PySpark, AWS, Python, Google-Colab, Notebook

## Observations
	
**Number of Vine reviews and non-Vine reviews?**	

![Review_1](https://user-images.githubusercontent.com/83256206/137972301-a71c9e10-1ad9-4714-9c2f-5de80f54198d.jpeg)


- There were 170 Vine reviews.
- There were 37,840 non-Vine reviews. 
  
**How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**	

![Review_2](https://user-images.githubusercontent.com/83256206/137972354-d61b4251-7d15-42d3-8e40-209101d15671.jpeg)


- 5 star reviews of vine reviews were 65.
- 5 star reviews of non_vine reviews were 20612.

**Percentage of 5 star reviews for vine and non_vine reviews?**	

![Review_3](https://user-images.githubusercontent.com/83256206/137972391-e2b10b98-33c3-4986-a86f-e6260ff3e98b.jpeg)


- 5 star reviews for vine were 38.2%.
- 5 star reviews for non_vine were 54.4%.

## Summary

Only 38.2 percent of 5 star Vine reviews are in the sample, compared to 54.4 percent of 5 star non-Vine ratings, indicating that there is no bias. Because 170 of the 37,840 evaluations were from Vine users, I feel there is a lack of proportion in the data set, which might lead to a lack of representation in the study.


