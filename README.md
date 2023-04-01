# Movie-Recommender-System

This is a movie recommender system that uses various algorithms to provide personalized movie recommendations to users. The dataset includes movie metadata, user ratings, and links to IMDB and TMDB. The recommender system uses item-based collaborative filtering, cosine similarity, and Pearson correlation to suggest movies to users.

### Requirements

* Python 3.x
* TuriCreate
* IMDbPY
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* nltk

### Installation

* pip install turicreate
* pip install imdbpy

### Usage

1. Download the dataset files: movies_metadata.csv, links.csv, and ratings.csv.
2. Import the necessary libraries and load the datasets into the script.
3. Merge the ratings and links datasets.
4. Clean and preprocess the data.
5. Calculate weighted ratings and visualize the results.
6. Create TuriCreate SFrame for the ratings dataset.
7. Train the item similarity recommender, cosine similarity recommender, and Pearson correlation recommender models.
8. Test the recommender system with a sample user and display the recommendations.
9. Evaluate the performance of the recommender models.

### Link to Kaggle Data

https://www.kaggle.com/code/rounakbanik/movie-recommender-systems/notebook
