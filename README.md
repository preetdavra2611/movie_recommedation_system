# 🎬 Movie Recommendation System

A content-based movie recommender built with Python and scikit-learn.

## How it works
- Combines movie overview, genres, and keywords into a feature string
- Uses TF-IDF vectorization to convert text to numerical vectors
- Computes cosine similarity between all movies
- Returns the top N most similar movies for any input title

## Tech Stack
Python | pandas | scikit-learn | TF-IDF | Cosine Similarity

## Dataset
TMDB 5000 Movies Dataset

## Sample Output
Input: "The Dark Knight"
Output: Batman Begins, The Dark Knight Rises, Batman Returns...
