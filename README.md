# Amazon Vine Analysis

# Overview of Analysis

For this project I conducted an analysis of Amazon reviews to determine if bias exists between Amazon Vine and Non-Amazon Vine reviewers. This analysis looked at video game reviews. I used PySpark through Google Colab to pull and clean the data, Amazon AWS to host the data, and PostGres SQL to hold the data tables. An analysis in Google Colab was then conducted to compare paid Vine reviewers vs non-paid reviewers to determine if any bias exists.  

# Results

The results revealed that a majority of video game reviewers were non-paid users, meaning they were not part of the Vine program. In the analysis, 94 were identifed as paid Vine reviewers while 40,471 were not unpaid reviewers. Of the paid Vine subscribers, 48, or 51%, left a 5-star review compared to 15,663, or 38%, of unpaid reviewers.

## Total Number of Reviews
![Vine](https://user-images.githubusercontent.com/112994018/212190138-9b990a0d-0176-4ede-b055-0c6d8dd68004.PNG)

## Number of 5-Star Reviews 
![5star](https://user-images.githubusercontent.com/112994018/212190147-b977dbae-5688-42d5-be74-7a6cf958d0cd.PNG)

## Percentage of 5-star Reviews
![percent5](https://user-images.githubusercontent.com/112994018/212190161-4d75afcf-f322-4a77-bb65-f854aea41d1c.PNG)

# Summary
After reviewing the results, there is argument that paid Vine members are more likely to leave a 5-star review compared to unpaid reviewers. Because the sample size of paid reviewers was so small for the video game analysis, it is hard to draw a definitive conclusion though. Perhaps an analysis of a different dataset to supplement the data could help with developing a stronger conclusion of whether bias exists or not.  
