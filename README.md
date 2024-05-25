# Movie Recommendation System

## Introduction:
The project involves building a movie recommendation system using Python and various libraries like Pandas, NumPy, and Streamlit. The system recommends movies based on textual data such as movie summaries and genres.

## Data Collection and Preprocessing:
First, the dataset is loaded from a CSV file stored in Google Drive. Exploratory Data Analysis (EDA) is conducted to understand the dataset's structure, including features like movie title, genre, and overview. Null values are handled, and relevant features are selected for the recommendation system. Text data preprocessing techniques such as combining features and NLP are applied.

## Building the Recommendation System:
The recommendation system is built using CountVectorizer for text feature extraction and cosine similarity calculation between movies. A function is implemented to recommend similar movies based on user input.

## Saving the Model:
The trained model, including the movie dataset and similarity matrix, is saved using the pickle library for future use.

## Streamlit Application Setup:
A Streamlit application is created to provide a user-friendly interface for the recommendation system. The layout includes sections for movie selection, recommendation trigger, and display of recommended movies.

## Fetching Movie Posters:
A function is implemented to fetch movie posters using The Movie Database (TMDb) API, enhancing the user experience by providing visual representations of recommended movies.

## Displaying Recommended Movies:
Upon user request, the recommendation function is triggered, and the recommended movie titles along with their posters are displayed in the Streamlit application.

## Conclusion:
The movie recommendation system is successfully implemented and deployed on Streamlit, providing users with personalized movie suggestions based on their preferences.





