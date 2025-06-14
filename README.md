# 🎬 Netflix Movie Recommender System

The **Netflix Movie Recommender** is a personalized recommendation system that suggests movies to users based on their preferences. Built using machine learning techniques like **Content-Based Filtering** and **Collaborative Filtering**, it replicates the intelligent movie suggestion experience similar to Netflix.

## 🚀 Features

- 🔍 **Search your favorite movie**
- 🎯 Get **Top 10 similar movie recommendations**
- 📊 Based on genres, cast, crew, overview, and ratings
- 🌐 Web app built using Flask with interactive frontend
- 🧠 Utilizes **TF-IDF**, **cosine similarity**, and optional **surprise** or **SVD** models

## 🧠 Recommendation Techniques

The system uses:

- **Content-Based Filtering**: Uses movie metadata (title, genre, overview, cast, crew) to recommend similar movies using TF-IDF + cosine similarity.
- **Collaborative Filtering (optional)**: Uses user ratings (via SVD or surprise package) to recommend movies based on user behavior.

## 📁 Project Structure

