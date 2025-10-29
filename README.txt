#  Movie Recommendation System

This project recommends similar movies based on content using data from TMDB.

## Overview
- Cleaned and merged datasets from TMDB (movies and credits)
- Extracted key features (overview, genres, keywords, cast, crew)
- Combined text into “tags” and applied CountVectorizer
- Used cosine similarity to find top 5 most similar movies

## Skills Demonstrated
Python · Pandas · Scikit-learn · Feature Engineering · Data Preprocessing · Data Analytics

## How to Run
1. Clone or download the repository.
2. Place 'tmdb_5000_movies.csv' and 'tmdb_5000_credits.csv' in the same folder.
3. Open 'movie_recommendation_system.ipynb' in Jupyter Notebook.
4. Run all cells.

##  Example Output
Movies similar to “Avatar”:
- Aliens  
- Apollo 18  
- The Book of Life  
- Brothers  
- Guardians of the Galaxy
