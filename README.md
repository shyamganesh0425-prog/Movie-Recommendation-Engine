# 🎬 Movie Recommendation Engine

A simple movie recommendation system built using **Python and NumPy**.

## 📌 Project Description

This project creates a **2D user-movie rating matrix**, where rows represent users and columns represent movies.

* Ratings range from **1 to 5**
* `0` represents a movie that the user has not watched
* The system calculates **Cosine Similarity** to find users with similar movie preferences
* Based on similar users' ratings, the system recommends the **Top 3 movies** that the selected user has not watched

## 🛠️ Technologies Used

* Python
* NumPy
* Jupyter Notebook

## 🧠 NumPy Concepts Used

* `np.array()`
* `np.dot()`
* `np.linalg.norm()`
* `np.argsort()`
* `np.where()`

## ⚙️ How It Works

1. Create a user-movie rating matrix.
2. Enter a User ID.
3. Calculate similarity between users using Cosine Similarity.
4. Find movies that the selected user has not watched.
5. Calculate recommendation scores based on similar users' ratings.
6. Sort the movies based on their scores.
7. Display the **Top 3 Recommended Movies**.

## 🎯 Project Goal

To recommend the **Top 3 unwatched movies** for a user based on the movie preferences of similar users.

## 📂 Files

* `Movie_Recommendation_Engine.ipynb` — Complete project notebook

## 👨‍💻 Author

Shyam Ganesh K
