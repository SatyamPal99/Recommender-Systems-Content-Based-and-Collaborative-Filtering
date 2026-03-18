# 🎬 Recommender Systems Assignment

## Overview
This project implements multiple recommendation system techniques using the MovieLens dataset. It covers both traditional and advanced approaches including content-based filtering, collaborative filtering, matrix factorization, hybrid models, deep learning, reinforcement learning, and explainability.

The goal is to analyze, implement, and compare different recommender system techniques.

## Features
- Content-Based Filtering (TF-IDF, User Profiles)
- Collaborative Filtering (User-Based & Item-Based)
- Matrix Factorization (SVD)
- Hybrid Recommendation Model
- Neural Network-Based Recommender
- Reinforcement Learning Recommender
- Explainability (SHAP, LIME, k-NN explanations)

# Optional Libraries:
-pip install tensorflow
-pip install scikit-surprise

## Dataset
- **Dataset:** MovieLens (ml-latest-small)
- **Files Used:**
  - `movies.csv`
  - `ratings.csv`

## Download: https://grouplens.org/datasets/movielens/

## How to Run

-Open Jupyter Notebook:

-jupyter notebook

-Open the .ipynb file.

-Update dataset path:

movies = pd.read_csv("path_to_movies.csv")
ratings = pd.read_csv("path_to_ratings.csv")

-Run all cells:
Kernel → Restart & Run All

