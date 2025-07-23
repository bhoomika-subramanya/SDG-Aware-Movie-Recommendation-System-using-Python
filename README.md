# 🎬 SDG-Aware Movie Recommendation System

A socially responsible, intelligent movie recommendation system that maps films to relevant **Sustainable Development Goals (SDGs)** using natural language processing on movie overviews.

> 🌍 Powered by the TMDb API and aligned with the United Nations 2030 Agenda for Sustainable Development.

---

## 📌 Project Overview

This project utilizes the `tmdb_5000_movies.csv` dataset and maps each movie's description to specific **SDGs** (like Quality Education, Gender Equality, Climate Action, etc.) based on keyword matching. The system allows users to:

- 🔍 Search for movies by title
- 🎯 Select SDGs to filter relevant content
- 🎭 Filter recommendations by genre
- 👍 Provide feedback with like/dislike buttons
- 📽️ View movie posters using the TMDb API

---

## 🧠 Sustainable Development Goals (SDGs) Mapped

| SDG Number | Goal |
|------------|------|
| SDG 4      | Quality Education |
| SDG 5      | Gender Equality |
| SDG 10     | Reduced Inequalities |
| SDG 13     | Climate Action |
| SDG 16     | Peace, Justice & Strong Institutions |

---

## 📁 Project Structure
├── rec_app.py # Main Streamlit app
├── sdg_mapping.py # SDG tagging logic for preprocessing
├── tmdb_5000_movies.csv # Movie dataset from TMDb
├── requirements.txt # List of dependencies
└── README.md # Project documentation

