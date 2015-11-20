## Introduction
This project looks into the review dataset provided by Yelp. 
In particular, I will be exploring the review of top reviewers (called Influencers) on whether it will have an impact on the businesses it reviewed, ie to see if it results in businesses getting better reviews (star ratings) subsequently.

## Method
For this analysis, we will be using the review, business and users dataset.
From the users, we will identify the top reviewers using predictive analysis. 
We will run a random tree prediction of all the variables in the users dataset to find out what are the key variables that will determine whether the user is 'popular'. 
From the top 2-3 variables we will use it to rank to get the top reviewers, which we will identify as 'influencers"
From the influencers, we will identify what are the businesses they have reviewed through. 
We will take the business which is given the lowest score ("stars") by the influencer and plot all their reviews, to see if there is an improvements in the reviews subsequently.
