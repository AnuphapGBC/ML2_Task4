# ML2_Task4
Task 4 - Movie Recommenders

Task: Build a Movie Recommender system with the following methods:

Popularity
Content Filter
Collaborative Filter
Matrix Factorization
Hybrid
Also, try the following libraries on the dataset:

Turicreate
Surprise
Dataset: MovieLens 20M 

Source: https://grouplens.org/datasets/movielens/20m/

Hints:

1. Read Movies.csv, Ratings.csv and Tags.csv. No need for genome-scores.csv, genome-tags.csv

2. Create content filtering method on metadata obtained from merging movies and tags

3. Metadata should be formed from joining all tag field for each movie_title.

4. Build a Tfidf Vectorizer model and TruncatedSVD for Content filter - Latent matrix 1 on this data

5. Create a Collab filter on User Movie matrix (formed from pivot table on ratings data)

6. Create a Latent matrix 2 on this data

7. Code hybrid model
