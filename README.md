# 🎬 Movie Recommender System

This project is a **content-based movie recommender system** built using Python and machine learning libraries. It suggests movies based on a lsited input by analyzing textual metadata such as genres, keywords, cast, and crew.

## 📘 Project Overview

The system uses a dataset of popular movies and applies natural language processing (NLP) techniques to recommend movies that are similar to the one entered by the user.

## 🔍 Key Features

- Takes a movie title as input and returns a list of  5 similar movies
- Utilizes `CountVectorizer` to transform metadata into feature vectors
- Calculates similarity using **cosine similarity**
- Lightweight and works in a Jupyter Notebook

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn (`CountVectorizer`, `cosine_similarity`)
- Jupyter Notebook

## 📄 File Description

- `Movie recomder system.ipynb`:  
  The main Jupyter Notebook that includes all the code for data preprocessing, feature extraction, similarity scoring, and movie recommendation.

## 🎯 How It Works

1. Read and clean the dataset
2. Combine important textual metadata into a single column
3. Convert the combined text into a matrix of token counts
4. Compute cosine similarity between movies
5. Recommend top 5 movies similar to the selected one

## 🚀 Sample Output

> **Input:** *"The Dark Knight"*  
> **Recommendations:** *"Batman Begins"*, *"The Dark Knight Rises"*, *"Man of Steel"*, *"Inception"*,.

## 🧠 Learning Outcome

- Built a functioning recommendation engine from scratch
- Applied vectorization and cosine similarity in practice
- Learned real-world application of NLP for personalized recommendations



Feel free to ⭐ the repo if you like this project!
