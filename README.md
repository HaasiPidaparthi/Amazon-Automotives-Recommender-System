# Amazon Automotive Products Recommender System
Team: Haasitha Pidaparthi, Daniel Kim, Simrandeep Singh

Dataset Source: UCSD - Amazon Review Data (2018)
https://nijianmo.github.io/amazon/index.html#subsets

## Motivation
* Most online e-commerce sites use some type of recommendation system
  * Amazon uses item-based collaborative filtering
* Amazon Automotive product reviews are very dynamic and lengthy at times
* The group wanted to gain an understanding of how Amazon uses the review data as a part of their recommendation system

Three different models were used to make predictions
* SciKit-Learn Library: Linear Regression, SVC, Gradient Boost, KNN, Gaussian Naive Bayes, and Random Forest algorithms
* Surprise Library: KNNBasic (User-based Collaborative filtering), SVD (Matrix Factorization based), Co-Clustering (Cluster-based), Slope One (Item-based Collaborative filtering)
* Tensorflow Keras: User Embeddings, Item Embeddings
