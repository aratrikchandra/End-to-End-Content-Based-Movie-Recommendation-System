# End to End Content Based Movie Recomandation System Using Streamlit
A Recommender system, or a recommendation system, is a subclass of information filtering system that seeks to predict the “rating” or “preference” a user would give to an item.Simply, Recommender systems aim to predict users’ interests and recommend product items that quite likely are interesting for them.
Typically there are three types of recommendation system are there :
<p align="center">
<img src = "https://github.com/Arupsau/End-to-End-Movie-Recomandation-System-Using-Streamlit/blob/main/Images/Types-of-Recommendation-Systems.png">
</p>
In this recomandation system content based Recommandation system is used to recomand the movies.It uses attributes such as genre, director, description, actors, etc. for movies, to make suggestions for the users. The intuition behind this sort of recommendation system is that if a user liked a particular movie or show, he/she might like a movie or a show similar to it.

**Dataset :** 

I will be using (https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) the TMDB-500 dataset for this project simply because it provides me with many columns to work with which have very useful information like the plot of movie, details about the cast, crew, directors, duration of the film,run time etc. This will help me get insights for my data analysis. Furthermore I would be using Cosine Similarity Matrix to determine how similar the documents are irrespective of their size. I will be using features like ‘genres’, ‘Credits’, ‘overview’, ‘Keywords’ from my TMBD-500 dataset for my Content Based Recommendation System.

**Required Libraries :**

* Numpy: Used for working with arrays.
* Pandas: Used for data analysis.
* Matplotlib.pyplot: Used for visual representation like plotting graphs.
* Sklearn: Used for making use of Machine learning tools.
* AST: This module helps python application to process trees of the python abstract syntax grammar.

**Data Preprocessing :**

* Load the dataset from kaggle--movies.csv and credits.csv
* Check if it has any null values or not
* Take the required columns for our analysis
* Do data cleaning
* Use CountVectorizer to convert a collection of text documents to a matrix of token counts
* Use cosine similarity matrix to understand the overview column and identify similar patterns and structure from it
* Save the model weights using pickle

**Deployment :**

Deployment is done using streamlit and make a web application movie recommandation system.
<p align="center">
<img src = "https://github.com/Arupsau/End-to-End-Movie-Recomandation-System-Using-Streamlit/blob/main/Images/Recommandation_System.png">
</p>

**Future Work :**

In future , I will try to use Collaborative Filtering and Hybrid Recommandation System. Also I will try to add description about the movies and  trailer of the particular recommanded movies using API fetch.
