Movie Recommendation System

This project is a movie recommendation system built in Python. It uses TMDb movie metadata and user ratings to suggest movies.

Datasets:

tmdb_5000_movies.csv: details about movies (title, genres, cast, crew, etc.)

ratings_small.csv: user ratings with userId, movieId, and rating

Main Features:

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Content-Based Filtering using TF-IDF and cosine similarity

Collaborative Filtering using matrix factorization (SVD)

Hybrid approach combining both methods

Setup and Run

Clone the repository:

git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system


Install required dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn scikit-surprise


Launch Jupyter Notebook:

jupyter notebook final_result.ipynb


Run the notebook cells step by step to:

Load the datasets

Clean and preprocess the data

Train the recommendation models

Generate movie recommendations

Example:

Input: Inception

Output: List of top recommended movies similar to Inception

Results:

Content-based recommends movies with similar genres/keywords

Collaborative filtering recommends based on user preferences

Hybrid gives better overall results
