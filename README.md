# Kaggle competition: H&M Fashion Recommendations
My solution to the Kaggle competition predicting H&amp;M personalized fashion recommendations (**FINAL RANKING: 58th / 2952 teams - silver medal)**

https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/overview

**Problem premise:** H&M provided 2 years of customer transaction data, and our goal was to recommend the 12 articles each customer was most likely to purchase in the 7 days immediately after the end of the training set (9/23/20 - 9/29/20).

**My approach:** I used a two-fold approach to build my final recommendations: 
1) I generated a list of potential candidates for each possible customer
2) I used a Gradient Boosting Decision Tree (GBDT) Ranker model to sort those candidates for each customer, and selected the top 12 highest-scored options as my recommendations.
