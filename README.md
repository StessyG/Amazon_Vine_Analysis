# Amazon_Vine_Analysis
# Overview of the analysis

The purpose of this analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 
In this analysis, different tools were used such as PySpark, Pandas, and SQL to determine if there is any bias toward favorable reviews from Vine members in our dataset.  

Dataset url: "https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Books_v1_01.tsv.gz"

Tools used:  PySpark, Jupyter Notebook, Google Colab Notebook, AWS Storage, SQL and pgAdmnin.

# Results:

The results of the analysis are as follow:

       How many Vine reviews and non-Vine reviews were there?

 - There was a total of 4,781 Vine reviews and 33,2395 non-Vine reviews.


       How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
 - There was a total of 170,404 five-star reviews     
 - There were 1,604 five-star Vine reviews 
 - There were 168,800 five-star non-Vine reviews

![image1](https://github.com/StessyG/Amazon_Vine_Analysis/blob/fa30361dc4ad281a797c54d0e000b6850d3ab785/images/image1.png)

       What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
 - The percentage of five-star Vine reviews over total five-star reviews was 0.94% 
 - The percentage of five-star non-Vine reviews over total five-star reviews was 99.06% 

![five_star](https://github.com/StessyG/Amazon_Vine_Analysis/blob/fa30361dc4ad281a797c54d0e000b6850d3ab785/images/five_star.png)


 - The percentage of five-star Vine reviews over total reviews was 0.48%
 - The percentage of five-star non-Vine reviews over total reviews was 50.06%

![five_total](https://github.com/StessyG/Amazon_Vine_Analysis/blob/fa30361dc4ad281a797c54d0e000b6850d3ab785/images/five_total.png)


 - The percentage of five-star Vine reviews over total Vine reviews was 33.55%
 - The percentage of five-star non-Vine reviews over total non-Vine reviews was 50.78%

![five_vine](https://github.com/StessyG/Amazon_Vine_Analysis/blob/fa30361dc4ad281a797c54d0e000b6850d3ab785/images/five_vine.png)



# Summary: 

The results of the analysis demonstrate that there is a low chance of positivity bias in the Vine program.
In fact, the percentage of five-star Vine reviews over the total number of five-star reviews was lower than 1%. Also, there was 0.48% of five-star Vinr reviews of the overall number of reviews.
In addition, there are 33.55% over five-star vine reviews of the total number of vine reviews, which is considerably lower compared to 50.78% of five-star non-Vine reviews over the total number of non-Vine reviews.
