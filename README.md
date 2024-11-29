# Movie Recommendation System

## Overview
This project implements a **Movie Recommendation System** using collaborative filtering (ALS) and regression-based models (Ridge and Lasso Regression). It predicts user preferences and generates recommendations for movies based on user behavior and movie features.

## Features
- **Collaborative Filtering (ALS):** Uses the Alternating Least Squares method to recommend movies based on user-item interaction.
- **Regression-Based Models:** Implements Ridge and Lasso regression for movie rating predictions using features like runtime, popularity, and genres.
- **Model Evaluation:** Compares models using RMSE (Root Mean Square Error).
- **Visualizations:** Heatmaps, histograms, and boxplots to analyze data and results.

## Dataset
The project uses the [Kaggle Movies Metadata](https://www.kaggle.com/rounakbanik/the-movies-dataset) dataset, which contains:
- Movies metadata (genres, runtime, popularity, etc.).
- User ratings.

## Project Structure
- **data/**: Contains the movies and ratings datasets.
- **notebook/**: Includes the Jupyter notebook for exploratory data analysis and model building.
- **src/**: Contains Python scripts for modular execution of the project.

## Prerequisites
- Python 3.8 or higher
- Spark 3.0 or higher (for PySpark)
- Jupyter Notebook (for exploration and visualization)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Movie-Recommendation-System.git
   cd Movie-Recommendation-System
