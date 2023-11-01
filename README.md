# NETFLIX RECOMMENDATION APP 🎥

 A project inspired by Netflix's movie recommendation system. This application makes movie recommendations easy and fun by using a Content-Based Recommender System.

## 🎬 Project Overview

The Netflix Recommendation App is built to help you discover new movies you might search,love. It uses a unique approach to provide movie recommendations based on the content of the movies you enjoy. 
The core concept behind this system is the use of Cosine Similarity to quantify the similarities between movies using various attributes such as genres, actors, and more.

## How Cosine Similarity Works

Cosine Similarity is a mathematical technique that measures the cosine of the angle between two non-zero vectors in an n-dimensional space. In the context of this app, it calculates the similarity score between movies. Here's how it works:

Data Collection: The app collects data on various attributes of movies, such as genres, actors, and more.

Vectorization: Text data is transformed into numerical vectors using techniques like Count Vectorization.

Similarity Calculation: Cosine Similarity is applied to these vectors to calculate how similar one movie is to another.

Recommendations: Based on the similarity scores, the app recommends movies similar to the ones you like or search for.

![image](https://github.com/Harinivas44/Netflix_Recommendation_App/assets/75987360/4cb28d6e-8abb-49ab-a0fd-c38cf7dd9a28)


## 🍿 Movie Review Prediction

In addition to recommending movies, this app also includes a model for predicting whether a movie review is good or bad. 
It uses a Naive Bayes classifier to classify reviews as either positive or negative. The reviews can help you gauge the public opinion on a movie.



