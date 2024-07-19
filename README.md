# Movie-Recommendation

This project is a movie recommendation system that suggests similar movies based on a user's favorite movie. The system leverages machine learning techniques to find and recommend movies with similar features.

#Project Overview

The goal of this project is to build a recommendation system that suggests movies similar to a user's input based on various features like genres, keywords, tagline, cast, and director. The system uses text data from movies and calculates similarity using cosine similarity.

#Features

Data Collection: Loads movie data from a CSV file.
Pre-processing: Handles missing values and combines relevant features.
Feature Extraction: Converts textual data into numerical vectors using TF-IDF.
Similarity Calculation: Measures similarity between movies using cosine similarity.
User Input: Accepts a movie title from the user and provides similar movie recommendations.

#Requirements

Python 3.x
Libraries: numpy, pandas, scikit-learn, difflib


#Notes

Ensure your movies.csv file is correctly formatted with the required columns.
You can modify the list of selected features based on your preferences for better recommendations.

#License
This project is licensed under the MIT License - see the LICENSE file for details.

#Acknowledgements

Inspired by various movie recommendation systems and tutorials.
