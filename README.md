# Movie Recommender System using Streamlit

This repository contains a Streamlit app that implements a movie recommender system based on user-selected movies. The app suggests similar movies by leveraging movie similarity scores and utilizes The Movie Database (TMDb) API to fetch movie posters.

## Requirements

Before running the Streamlit app, make sure you have the required libraries installed:

- Streamlit
- Requests
- Pandas

You can install these libraries using the following command:
```
pip install streamlit requests pandas
```
 How to Use:
1) Clone this repository to your local machine.
```
git clone https://github.com/OmBirari/movie-recommender.git
```
2) Navigate to the repository directory.
```
cd movie-recommender
```
3) Run the Streamlit app.
```
streamlit run movie_recommender.py
```
The Streamlit app will open in your default web browser. Select a movie from the dropdown list and click the "Show Recommendation" button to see similar movie recommendations.
App Overview
The movie_recommender.py script implements a movie recommender system using the following steps:

Load movie data and similarity scores from pickle files.
Display a dropdown list of movies using Streamlit.
Upon clicking the "Show Recommendation" button, the app fetches similar movies and displays their names and posters.
Functionality
fetch_poster(movie_id): Fetches the poster image URL for a given movie ID using the TMDb API.

recommend(movie): Recommends similar movies based on the selected movie. It calculates movie similarity scores and fetches the posters for the recommended movies.

Acknowledgments
This app is developed using Streamlit and utilizes the TMDb API for fetching movie data and posters. It demonstrates the concept of collaborative filtering for movie recommendations.

Data Sources
The Movie Database (TMDb): https://www.themoviedb.org/







