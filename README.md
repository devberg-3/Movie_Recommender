# Movie Recommender System

This project is a Movie Recommender System that suggests movies based on a selected movie. It uses the TMDB dataset and cosine similarity to find movies similar to the selected movie and display their posters.

## Features

- Select a movie from a dropdown list.
- Get a list of 5 recommended movies with their posters.
- Uses cosine similarity to find similar movies.
- Fetches movie posters using TMDB API.

## Requirements

- Python 3.x
- Streamlit
- pandas
- scikit-learn
- requests
- pickle


## Usage

1. Open the Streamlit app in your browser.
2. Select a movie from the dropdown list.
3. Click the "Recommend" button to get the list of recommended movies and their posters.

## Files

- `app.py`: The main Streamlit app file.
- `similarity.pkl`: Precomputed cosine similarity matrix.
- `movie_list1.pkl`: Pickled dictionary containing movie details.
- `tmdb_5000_movies.csv`: Dataset file containing movie details.
- `tmdb_5000_credits.csv`: Dataset file containing movie credits.

