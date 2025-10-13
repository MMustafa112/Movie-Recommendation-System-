# 🍿 Task 5: Movie Recommendation System
Project Goal
This project implements a foundational Collaborative Filtering system designed to recommend movies to users based on their historical ratings. This is the core engine behind major streaming and e-commerce platforms.

Key Concepts Covered
Collaborative Filtering: Predicting a user's preference by leveraging the tastes of other users (or the properties of other items).

User-Item Matrix: Creation of the critical data structure (Users × Movies) to calculate similarities.

Similarity Metrics: Used Cosine Similarity to quantify the closeness of user tastes or movie profiles.

Methodology & Advanced Implementation
The project compared two distinct approaches to meet the core requirements and the bonus challenges:

User-Based Collaborative Filtering (Core):

Finds "Movie Twins" (users with similar rating patterns).

Recommends movies highly rated by those twins that the target user hasn't seen.

Item-Based Collaborative Filtering (Bonus):

Finds "Movie Twins" (movies with similar rating patterns across users).

Predicts a rating for a new movie based on how the user rated similar movies in the past.

🛠️ Technologies
Python

Pandas (Data Transformation and Matrix Creation)

NumPy (Matrix Operations)

Scikit-learn (cosine_similarity for the core algorithm)

Matplotlib (Visualization, if included)

# DATA SOURCE

https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset/data
