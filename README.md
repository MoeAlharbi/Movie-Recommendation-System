# Movie Recommendation System

## Overview
This project implements a **Movie Recommendation System** using collaborative filtering (ALS) and regression-based models (Ridge and Lasso Regression). It predicts user preferences and generates recommendations for movies based on user behavior and movie features.

## Features
- **Collaborative Filtering (ALS):** Uses the Alternating Least Squares method to recommend movies based on user-item interaction.
- **Regression-Based Models:** Implements Ridge and Lasso regression for movie rating predictions using features like runtime, popularity, and genres.
- **Model Evaluation:** Compares models using RMSE (Root Mean Square Error).
- **Visualizations:** Heatmaps, histograms, and boxplots to analyze data and results.

## Dataset

This project uses the [MovieLens Dataset](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset), which contains 20 million ratings and 465,000 tag applications applied to 27,000 movies by 138,000 users.

### Steps to Download the Dataset

1. **Visit the Dataset Page**:
   - Go to the [MovieLens Dataset on Kaggle](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset).

2. **Download the Dataset**:
   - Click on the **Download** button on the Kaggle page.
   - Extract the downloaded `.zip` file into the `data/` folder of this project.

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
