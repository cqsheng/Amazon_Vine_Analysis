# An analysis of Amazon reviews with Vine

## Overview of Project
    This project is used to determine if there are any favorable bias with products with vine members on Amazon.
### Purpose
    The purpose of this project is to analyze the product reviews on amazon by looking at all the reviews for a product> Then grouping them together and filtering based on five star reviews from Vine members and non Vine members to see if there are any bias towards favorable reviews from Vine members.

## Results
    The Data was analyzed and split into filtered dataframes, the total number of reviews and 5 star reviews were then summed up for paid and unpaid member reivews using whether they had the Vine member or not to determine the percentage of 5 star reviews over total reivews. The results for paid and unpaid is pictured below.
    
![](/images/paid.png)
![](/images/unpaid.png)

### As can be seen in the pictures above:
*There were 47 reviews for Vine members, and much more for non members with 8362 reviews.
*There were 15 5 star reviews for Vine members, and 4332 5 star reviews for non members.
*There were around 31.9% of 5 star reviews for Vine members, and actually a higher percentage of 51.8% of 5 star reviews for non members.

## Summary
    Although the number of reviews for Vine members isn't alot, some conclusions can still be drawn from this.
### There is no evidence to suggest that the vine members have positivity bias, since they only get 31.9% of 5 star reviews compared to 51.8% for non vine members. If anything they receive worse reviews although future analysis would be needed to conclude that.
### There is no analysis done to see if the average review score is higher even though there are more 5 star reviews for non vine members, the average score could still be lower than vine members if they are more inclined to give 1 star reviews. An analysis using the average for the column "star_rating" instead of the number of 5 star reviews would determine if there are indeed any positivity bias for the average review score for vine members and non vine members.
