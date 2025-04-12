# 🎬 Movie Recommender System

This is a **Content-Based Movie Recommender System** built using Natural Language Processing (NLP) and Machine Learning. Given a movie title, it suggests 5 similar movies based on genres, keywords, cast, and crew.

## 🚀 Demo

A Streamlit web app allows users to select a movie from a dropdown and get recommendations instantly.

## 📁 Dataset

The project uses the [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

## 🛠️ Features

- Merged and cleaned movie and credits data
- Extracted and processed tags from genres, keywords, cast, crew, and overview
- Vectorized tags using CountVectorizer
- Measured similarity using cosine similarity
- Built a simple UI with Streamlit for user interaction

## 🧰 Tech Stack

- Python 🐍
- Pandas & NumPy
- Scikit-learn
- Streamlit
- Pickle (for model saving)

## 📦 Installation

1. Clone the repository:
   ```bash
   [git clone] (https://github.com/rudrapratap19/content-based-movie-recommender.git)
   cd content-based-movie-recommender
