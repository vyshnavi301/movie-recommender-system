
# movie-recommender-system
This repository contains code for Recommendation of differents movies. Developed using streamlit and python. Website is hosted on heroku.

It's live at https://tarumani301.herokuapp.com/




## About Project

A content based movie recommender system using cosine similarity
Based on the past user behavior, it recommends the movies to users based on their similarity. 
So the system adapts and learns the user behavior and suggests the items based on that behavior.

## About Dataset
The Dataset we used is TMDB 5000 Movie Dataset.
The dataset can be found in kaggle.

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv
## Dependencies
Web Technologies
: streamlit

Machine Learning Library In Python : Numpy , Pandas , Scipy
## development 
The development of this app inclues four stages

1) Data Collection
2) Backend Programming - The entire backend programming has been done in python, using pandas, numpy, etc.

3) Cleaning and Organizing the data.

4) Building a Recommender System based on Content Based Filtering.
we used Cosine Similarity to Build the Recommender.

Cosine similarity is a metric used to measure how similar two items are. Mathematically it calculates the cosine of the angle between two vectors projected in a multidimensional space. Cosine similarity is advantageous when two similar documents are far apart by Euclidean distance(size of documents) chances are they may be oriented closed together. The smaller the angle, higher the cosine similarity.


5) UI - The User Interface was built based on python module called Streamlit.

6) Hosting the App on Heroku.