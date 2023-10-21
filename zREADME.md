## Introduction
This project aims to recommend movies based on their textual content, including genres, keywords, cast, and crew. The recommendation system uses cosine similarity to find movies with similar content and suggests them as recommendations.

## Requirements
Python 3
Libraries: numpy, pandas, scikit-learn, nltk

  Data
The code uses two datasets:

tmdb_5000_movies.csv: Contains movie details such as title, overview, genres, keywords, and more.
tmdb_5000_credits.csv: Contains movie credits, including cast and crew information.
Data Preprocessing
The code performs various data preprocessing steps, such as handling missing values, converting data, and creating a feature vector for each movie.

Recommendation
The recommendation system is based on cosine similarity, which measures the similarity between movie vectors. It suggests movies with the highest similarity to a given movie title.

Files
movie_dict.pkl: A pickle file containing a dictionary with movie details.
similarity.pkl: A pickle file containing the similarity matrix.
