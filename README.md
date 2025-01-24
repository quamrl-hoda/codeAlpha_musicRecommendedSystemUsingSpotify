
---

# 🎵 Music Recommendation System

This project implements a basic **music recommendation system** inspired by Spotify’s machine learning-based recommendation model. It predicts a user's likelihood of repeatedly listening to a song within a specific timeframe and generates personalized recommendations based on their listening history and interactions.

## 📋 Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [How It Works](#how-it-works)


---

## 📖 Introduction

This system uses collaborative filtering techniques, such as **K-Nearest Neighbors (KNN)**, to recommend songs to users based on their listening behavior. By analyzing a dataset of user-song interactions (indicating whether a song was repeatedly played), the model predicts songs that a user might enjoy but hasn’t listened to yet.

---

## ✨ Features

- Tracks user-song interaction data (e.g., repeated plays).
- Generates personalized song recommendations using collaborative filtering.
- Leverages **KNN** with cosine similarity to find similar songs or users.
- User-friendly structure for extension into advanced machine learning models.

---

## 🛠️ Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - [Pandas](https://pandas.pydata.org/) (data manipulation)
  - [NumPy](https://numpy.org/) (numerical operations)
  - [Scikit-Learn](https://scikit-learn.org/) (machine learning algorithms)

---

## 📊 Dataset

The dataset used in this project consists of:
- `user_id`: Unique identifier for each user.
- `song_id`: Unique identifier for each song.
- `played_repeatedly`: Binary flag (1 for repeated plays within a timeframe, 0 otherwise).


## ⚙️ How It Works

1. **Data Processing**: A user-song interaction matrix is generated to represent user preferences.
2. **KNN Model**: A K-Nearest Neighbors algorithm with cosine similarity is applied to find similar songs or users.
3. **Recommendation Generation**: Based on the KNN results, the system recommends songs that the user hasn’t interacted with but may enjoy.



   


---

🎧 **Happy Listening!**

If you have any questions or need help with the project, feel free to reach out!

--- 

