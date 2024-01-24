# movie-recommender-system
[https://movie-recommender-system-devidutta.streamlit.app/](https://movie-recommender-system-devidutta.streamlit.app/)

This repository contains the code and data for building a movie recommender system that uses content based filtering to suggest movies to users based on their preferences.

## Content Based Filtering
Content based filtering is a technique that uses the features of the items (such as genre, actors, director, etc.) to find the similarity between them and recommend the most similar items to the user. For example, if a user likes a movie that is a comedy and has Will Smith as an actor, the system will recommend other movies that are comedies and have Will Smith as an actor.

## Cosine Similarity
Cosine similarity is a measure of how similar two vectors are by calculating the cosine of the angle between them. It ranges from -1 to 1, where -1 means completely opposite, 0 means orthogonal (no similarity), and 1 means identical. Cosine similarity is used to compare the feature vectors of the movies and find the most similar ones to the user’s preference.

## Dataset
The dataset used for this project is the **TMDB 5000 Movie Dataset**, Metadata on ~5,000 movies from TMDb The dataset also includes movie metadata such as title, genres, release year, etc.

## Code
The code for this project is written in Python and uses the following libraries:

pandas: for data manipulation and analysis
numpy: for numerical computation and linear algebra
sklearn: for machine learning and data preprocessing
nltk: for natural language processing and text analysis
The code consists of the following steps:

Loading and exploring the dataset
Preprocessing the data and creating feature vectors for the movies
Computing the cosine similarity matrix for the movies
Defining a function to generate recommendations for a given movie title
Testing the system with some examples

## Results
The system is able to generate relevant recommendations for different movie titles based on the content features. For example, for the movie “The Matrix”, the system recommends the following movies:

The Matrix Reloaded
The Matrix Revolutions
The Terminator
Blade Runner
Inception

## Conclusion
This project demonstrates how to build a simple but effective movie recommender system using content based filtering and cosine similarity. The system can also be extended to use collaborative filtering or hybrid approaches to combine the advantages of both content based and user based methods.
