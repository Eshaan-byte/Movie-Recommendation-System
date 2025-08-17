# 🎬 Movie Recommendation System

A simple Movie Recommender Web App built with **Streamlit** that suggests similar movies based on a selected title.  
It uses a **content-based filtering** approach with precomputed similarity scores and fetches posters from **The Movie Database (TMDB) API**.

---

## 🚀 Features
- Select a movie from a dropdown list
- Get **top 5 recommended movies** with posters
- Fetches posters dynamically from **TMDB API**
- Simple and interactive UI powered by **Streamlit**

---

## 🛠️ Tech Stack
- **Python 3.10+**
- [Streamlit](https://streamlit.io/)
- [TMDB API](https://www.themoviedb.org/documentation/api)
- Pickle (for loading precomputed model data)
- Pandas & Requests

---

## 📂 Project Structure
Movie-Recommendation-System/
│
├── app.py # Streamlit app
├── model/
│ ├── movie_list.pkl # Movie metadata
│ ├── similarity.pkl # Precomputed similarity matrix
├── README.md # Project documentation
└── requirements.txt # Python dependencies
