# Bharat-Intern-Task-2
# Movie Recommendation System
This project implements a movie recommendation system using machine learning algorithms. The system suggests movies to users based on the similarity of movie plots. The recommendation process leverages text processing techniques and similarity measures.

## Features
### 1.Content-Based Filtering: 
The system recommends movies similar to the ones the user likes based on the similarity of movie descriptions.
### 2.Machine Learning Algorithms:
Utilizes the TfidfVectorizer to transform movie descriptions into numerical vectors and cosine similarity to measure the similarity between these vectors.
### 3.Efficient Search:
Uses difflib to find the closest matches to the user's input

## Libraries Used
### NumPy: For numerical operations.
### Pandas: For data manipulation and analysis.
### Difflib: For finding close matches in strings.
### TfidfVectorizer: For transforming text data into numerical vectors based on Term Frequency-Inverse Document Frequency.
### Cosine Similarity: For measuring the cosine of the angle between two vectors to determine similarity.

## How It Works
### Data Preprocessing: Movie descriptions are converted into TF-IDF vectors.
### Similarity Calculation: Cosine similarity is calculated between the vector of the input movie and all other movie vectors.
### Recommendation Generation: The top N movies with the highest similarity scores are recommended to the user.
