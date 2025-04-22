# Movie-watch-pattern-clustering
Movie watch pattern clustering
# Movie Watch Pattern Clustering

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-brightgreen)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-blueviolet)

A clustering analysis project that groups users based on their movie-watching behavior patterns, including watch time, genre preferences, and rating habits.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project applies K-Means clustering to analyze and segment users based on:
- **Watch Time**: Hour of day when movies are watched
- **Genre Preference**: Preferred movie genres
- **Rating Behavior**: Average ratings given to movies

The insights can be used for personalized recommendations, content scheduling, and marketing strategies.

## Features
- Data preprocessing pipeline (scaling + one-hot encoding)
- Optimal cluster determination (elbow method)
- K-Means clustering implementation
- Interactive visualizations
- Cluster profiling and interpretation

## Dataset
The dataset contains three key features:
1. `watch_time_hour`: Hour of day (0-23)
2. `genre_preference`: Movie genre (action, comedy, drama, thriller)
3. `avg_rating_given`: Average rating given (1-5 scale)

Sample data is provided in `movie_data.csv`. For larger datasets, consider using [MovieLens](https://grouplens.org/datasets/movielens/) data.

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/movie-watch-pattern-clustering.git
cd movie-watch-pattern-clustering
