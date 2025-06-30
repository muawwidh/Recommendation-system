# Movie Recommender System (Collaborative Filtering)

This project demonstrates how to build a movie recommender system using **item-item collaborative filtering**, inspired by the "Because you watched Movie X" feature on streaming platforms like Netflix.

## Project Overview

- **Goal:** Recommend similar movies to a given movie using collaborative filtering.
- **Dataset:** [MovieLens latest small](https://grouplens.org/datasets/movielens/) (`ratings.csv` and `movies.csv`)
- **Tech Stack:** Python, Pandas, NumPy, Scikit-learn, SciPy, Matplotlib, Seaborn, Jupyter Notebook

## Features

- Loads and analyzes the MovieLens dataset
- Builds an item-item similarity model (collaborative filtering)
- Uses k-Nearest Neighbors and/or SVD for recommendations
- Visualizes similarities and recommendations
- Explains key collaborative filtering concepts

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/movie-recommender-collab.git
cd movie-recommender-collab
```

### 2. Install dependencies
All dependencies are listed in requirements.txt.

```bash
pip install -r requirements.txt
```

### 3. Download the dataset

- Download the MovieLens dataset from the [official MovieLens page](https://grouplens.org/datasets/movielens/).
- Or download the file directly: [ml-latest-small.zip](http://files.grouplens.org/datasets/movielens/ml-latest-small.zip)
- Extract `ratings.csv` and `movies.csv` into your project directory.

### 4. Run the notebook
```bash
jupyter notebook movieRecommender.ipynb
```

Feel free to fork, use, or extend this project!
