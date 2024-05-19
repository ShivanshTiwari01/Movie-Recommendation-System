
# Movie Recommendation System

This is a movie recommendation system built using Python, Jupyter Notebook, and the `numpy`, `pandas`, and `sklearn` libraries. The system uses movie data from two datasets, `credits.csv` and `movies.csv`, to provide personalized movie recommendations.

## Overview

The movie recommendation system aims to suggest movies to users based on various factors such as genre, cast, crew, and keywords. It employs content-based filtering techniques to provide these recommendations.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- numpy
- pandas
- scikit-learn
- Jupyter Notebook

You can install the required libraries using pip:

pip install numpy pandas scikit-learn notebook

## Datasets
The system uses two datasets:

credits.csv: Contains information about the cast and crew of movies.
movies.csv: Contains information about movies such as title, genres, and keywords.
Ensure these CSV files are in the same directory as your Jupyter Notebook.

Usage
Clone this repository or download the files to your local machine.
Ensure you have the datasets (credits.csv and movies.csv) in the same directory as the Jupyter Notebook.
Open the Jupyter Notebook and run all the cells to see the movie recommendation system in action.
To start the Jupyter Notebook:

jupyter notebook movie_recommendation_system.ipynb

## Methodology
The recommendation system follows these steps:

Data Loading and Preprocessing: Load the datasets and clean the data.
Feature Extraction: Extract relevant features from the datasets, such as cast, crew, genres, and keywords.
Vectorization: Convert textual data into numerical vectors using techniques like TF-IDF.
Similarity Calculation: Calculate similarity between movies using cosine similarity.
Recommendation Generation: Generate and display movie recommendations based on the calculated similarities.

## Results
The system provides a list of recommended movies based on the input movie. It uses content-based filtering to find movies similar to the one provided by the user.
