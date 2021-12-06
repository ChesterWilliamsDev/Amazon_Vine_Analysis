# Amazon_Vine_Analysis

## Overview of the analysis
This analysis is being performed to assess the potential bias towards favorable reviews from the Amazon Vine members that recieve products from SellBy in exchange for a required review. The ETL process is being performed using Googlcolab, AWS, and pgadmin. 

## Results

### * How many Vine reviews and non-Vine reviews were there?
   There were a total of 4,992 reviews considered for this analysis using the major appliances review data set. 
 
### * How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
   The analysis showed there were 18 5 star reviews from the Vine sample and 1,963 5 star reviews from the non-Vine sample. 
    
### * What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
   The analysis showed Vine reviews represented a total of .9% of the 5 star review sample. Non-Vine reviews represented 99.08% of the 5 star review sample.

<img src="https://github.com/ChesterWilliamsDev/Amazon_Vine_Analysis/blob/main/images/reviews_1.png"/>

## Summary
  Based on the results from this analysis, the data does not indicate a positivity bias for reviews among the Vine program. Since the sample population of 5 star reviews of major appliances had less than 1% of reviews from the Vine program, it would be difficult to assume positivity bias based on this analysis. Statistical analysis using linear regression is recommended to investigate the statisical significance of the results from this dataset. 
