🎬 Movie Recommendation System
📌 Overview
This project is a Movie Recommendation System built using Machine Learning & Data Science techniques. It suggests movies to users based on their preferences, viewing history, or content similarity. The system leverages collaborative filtering and content-based filtering to provide accurate recommendations.

in this recommendatio we used movies dataset
we are working with various columns :
 budget
 homepage
 id
 original_language
 original_title
 popularity
 production_comapny
 production_countries
 release-date(not sure)

FEATURES

 Tag-Based Similarity: Creates a "tags" column combining overview, genres, keywords, cast, and crew.

Text Preprocessing:

Removes spaces from words to maintain consistency.

Applies stemming (e.g., "loving" → "love") to reduce words to their root forms.

Vectorization with CountVectorizer: Converts text into numerical vectors using Bag of Words (BoW) with a vocabulary size of 5000 words.

Cosine Similarity: Measures the similarity between movies based on their textual representations.

Movie Search & Recommendation:

Finds the closest movies based on user input.

Technologies Used
✔ Python (Pandas, NumPy)
✔ NLP Techniques (Stemming, Tokenization)
✔ Scikit-Learn (CountVectorizer, Cosine Similarity)
✔ NLTK (PorterStemmer for text preprocessing)

📂 Files Included
Dataset (tmdb_5000_movies.csv, tmdb_5000_credits.csv): Movie details & cast/crew information.

Preprocessing Script (movie_preprocessing.py): Cleans and processes data.

Recommendation Engine (movie_recommender.py): Core logic for similarity-based recommendations.

Jupyter Notebook (movie_recommendation.ipynb): Exploratory data analysis & visualization.

🎯 How It Works
Data Cleaning & Feature Selection: Merges movie metadata and selects relevant columns.

Text Preprocessing: Converts textual data into a processed format.

Feature Extraction: Uses CountVectorizer to generate a vector representation.

Computing Similarity: Calculates cosine similarity between movies.

Making Recommendations: Suggests movies based on highest similarity scores.



Returns the top N most similar movies.


