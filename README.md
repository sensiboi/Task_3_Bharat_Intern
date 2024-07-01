# TASK 3
## Movie Recommendation System
This repository contains a movie recommendation system developed using a dataset of movies and various machine learning techniques. The system recommends movies based on the similarity of genres, keywords, taglines, cast, and directors.

## Project Overview
The project focuses on building a recommendation system using the TF-IDF vectorization technique and cosine similarity to recommend movies similar to a user's favorite movie.

## Dataset
The dataset contains information about movies, including:

Movie ID
Movie Title
Movie Genre
Movie Language
Movie Budget
Movie Popularity
Movie Release Date
Movie Revenue
Movie Runtime
Movie Vote
Movie Vote Count
Movie Homepage
Movie Keywords
Movie Overview
Movie Production House
Movie Production Country
Movie Spoken Language
Movie Tagline
Movie Cast
Movie Crew
Movie Director
Steps and Code
1. Import Libraries
Necessary libraries such as pandas, numpy, sklearn, and difflib are imported to handle data processing and machine learning tasks.

2. Load Dataset
The dataset is loaded using pandas' read_csv method and the first few rows are displayed to understand the structure of the data.

3. Describe Data
The dataset is described to understand its basic statistics, data types, and shape.

4. Data Preprocessing
Relevant features are selected and missing values are filled to prepare the data for modeling.

5. Calculate Similarity
The selected features are combined into a single string for each movie, vectorized using TF-IDF, and cosine similarity scores are calculated.

6. Get User Input for Favorite Movie
The user is prompted to input their favorite movie, and the closest matching movie title in the dataset is identified.

7. Get Recommendations
Based on the similarity scores, the top 20 movies similar to the user's favorite movie are recommended and displayed.

## Predictions
The system recommends the top 20 movies based on the similarity scores.

## Example
For the favorite movie "Star Wars", the top 10 recommended movies are:

Finding Nemo
Big Fish
John Carter
Spider-Man
Shark Tale
Flight of the Intruder
El Mariachi
Shooting Fish
The Shaggy Dog
The Muse
## Conclusion
This movie recommendation system effectively suggests movies based on the user's favorite movie using a content-based filtering approach. The cosine similarity metric ensures that the recommendations are based on the closest match of movie attributes.
## Libraries
pandas
numpy
scikit-learn
difflib
