# CS562_Geo-tagged_data

## Analysis of Geo-tagged twitter or geo-social network data.

### Data:
	- https://www.yelp.com/dataset/documentation/json

### Abstract:
Today, one of the most influential leading consumer review sites is Yelp. Yelp contains a large dataset that computer scientists can use to analyze the social relationships and trends between the star rating (from 1 to 5) and reviews, the number of reviews, the type of business, and the number of customers. Our plan is to store, query, and analyze Yelp's large dataset. The main purpose of this project is to use various data analysis and mining tools to attain optimal accuracy of classifying and summarizing the data. Since the Yelp dataset only contain 10 cities around the world, we decided to use Las Vegas as our main city to do the analysis. Optimally, we are finding interesting patterns between the type of restaurant and the star rating of the restaurants in Las Vegas. The data analysis tools we used in this project were K-means++ cluster, Dynamic Time Warping, Singular-Value Decomposition, Latent Semantic Analysis and Random Forest Classifier.

### Problem Definitions:
	- Where are the highest rated restaurants located in Las Vegas? We want to cluster the restaurants by the geo-tagged data provided in the Yelp dataset, and calculate the average star of each cluster.
	- Can we predict the star rating if given some feature of the restaurant?
	- What is the relationship between locations and the star ratings, review amounts and other attributes in the data-set?
	- What patterns can we visualize for time versus the evolution of Yelp rating of the restaurants in Las Vegas?
	- What can text reviews tell us about the restaurants in Las Vegas? Our goal here is to cluster the text reviews of the restaurants and extracting categories in an unsupervised fashion. 

* Zhiyu Wang, wangzy95@bu.edu
* Chuan X Zheng, czheng78@bu.edu
* Chunxi Wang, tracycxw@bu.edu
