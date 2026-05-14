# 🎬 Movie Recommender System

A content-based movie recommendation system built with Python and Streamlit.  
The app recommends similar movies using cosine similarity and fetches movie posters dynamically from the TMDB API.

## 🚀 Features

- Recommend top 5 similar movies
- Content-based filtering
- Cosine similarity-based recommendation
- TMDB API poster integration
- Interactive Streamlit web app
- Simple and beginner-friendly UI

## 🧠 How It Works

1. Movie metadata is cleaned and processed.
2. Important text features are combined.
3. Text is converted into vectors.
4. Cosine similarity is calculated between movies.
5. The app returns the most similar movies based on the selected title.

## 🛠️ Tech Stack

- Python
- Pandas
- Scikit-learn
- Streamlit
- Pickle
- TMDB API

## 📁 Project Structure

```bash
ml-movie-recommender/
│
├── app.py
├── movies.pkl
├── similarity.pkl
├── requirements.txt
├── README.md
├── .gitignore
│
├── notebooks/
│   └── movie_recommender.ipynb
│
├── screenshots/
│   └── app_preview.png
│
└── src/
    └── recommender.py
