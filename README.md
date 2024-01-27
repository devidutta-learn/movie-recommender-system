# movie-recommender-system

### [https://movie-recommender-system-devidutta.streamlit.app/](https://movie-recommender-system-devidutta.streamlit.app/)

This repository contains the code and data for building a movie recommender system that uses content based filtering to suggest movies to users based on their preferences.

<img src="FireShot Capture 222 - Streamlit - movie-recommender-system-devidutta.streamlit.app.png">

## Technology

### Machine Learning
> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
<a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> 
<a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://numpy.org/images/logo.svg" alt="numpy" width="40" height="40"/> </a> 
<a href="https://scikit-learn.org/stable/" target="_blank" rel="noreferrer"> <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" alt="scikitlearn"  height="40"/> </a> 
<a href="https://www.nltk.org/" target="_blank" rel="noreferrer"> <img src="https://miro.medium.com/v2/resize:fit:1184/format:webp/1*YM2HXc7f4v02pZBEO8h-qw.png" alt="NLTK"  height="40"/> </a> 

### Web Development
> <a href="https://streamlit.io/" target="_blank" rel="noreferrer"> <img src="https://yt3.googleusercontent.com/ytc/AIf8zZSb7aWphJvsnl5ZQ7VaEfdultOKw3BR4h-fc8HhEg=s900-c-k-c0x00ffffff-no-rj" alt="Streamlit"  height="40"/> </a> 

### Tool
> <a href="https://www.jetbrains.com/pycharm/" target="_blank" rel="noreferrer"> <img src="https://storage.caktusgroup.com/media/blog-images/logo.png" alt="PyCharm" width="40" height="40"/> </a>
<a href="https://colab.research.google.com" target="_blank" rel="noreferrer"> <img src="https://colab.research.google.com/img/colab_favicon_256px.png" alt="colab" width="40" height="40"/> </a>
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> 
<a href="https://kaggle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kaggle/kaggle-original-wordmark.svg" alt="kaggle" height="50"/> </a> 

## Content Based Filtering
Content based filtering is a technique that uses the features of the items (such as genre, actors, director, etc.) to find the similarity between them and recommend the most similar items to the user. For example, if a user likes a movie that is a comedy and has Will Smith as an actor, the system will recommend other movies that are comedies and have Will Smith as an actor.

## Cosine Similarity
Cosine similarity is a measure of how similar two vectors are by calculating the cosine of the angle between them. It ranges from -1 to 1, where -1 means completely opposite, 0 means orthogonal (no similarity), and 1 means identical. Cosine similarity is used to compare the feature vectors of the movies and find the most similar ones to the user’s preference.

## Dataset
The dataset used for this project is the **TMDB 5000 Movie Dataset**, Metadata on ~5,000 movies from TMDb The dataset also includes movie metadata such as title, genres, release year, etc.



## Code
The code consists of the following steps:

Loading and exploring the dataset. 
Preprocessing the data and creating feature vectors for the movies.
Computing the cosine similarity matrix for the movies.
Defining a function to generate recommendations for a given movie title. 
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
