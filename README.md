# Project Title: Analysis of Spotify Music Trends and Artist Popularity

## Introduction
This project aims to analyze trends in music and artist popularity using data extracted from the Spotify API. The objective is to understand what factors contribute to the popularity of songs and artists on Spotify and to predict future trends.

## Problem Statement
With the vast amount of music available on Spotify, it's crucial to understand what makes a song or an artist popular. Are there certain characteristics of songs that make them more appealing to listeners? How do artists' popularity and their music's features correlate? This analysis seeks to uncover these patterns and provide insights that could be valuable for artists, record labels, and marketers.

## Data Collection
We utilized Spotify's API to gather detailed information on songs, albums, and artists. The data includes:

- **Album Information**: Album IDs, names, release dates, total tracks, URLs, types, image URLs, and artist IDs.
- **Artist Details**: Genres, popularity scores, follower counts, and images.
- **Song Metrics**: Song IDs, names, duration, URLs, popularity scores, explicitness, track numbers, disc numbers, and addition dates.
- **Audio Features**: Danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, and time signatures.

The data was collected in Python using functions to extract and organize information into a structured format for analysis.

## Data Processing
We merged the collected data into a comprehensive dataset. The merging process involved combining song, artist, and album details with audio features to create a rich dataset that provides a multi-dimensional view of the music.

## Analysis
Our analysis will focus on:

- **Trends Over Time**: How music characteristics and artist popularity have evolved.
- **Popularity Factors**: Identifying the features of songs and artists that are most associated with high popularity scores.
- **Genre Analysis**: Exploring the popularity of different genres and how genre preferences change over time.
- **Predictive Modeling**: Developing a model to predict song popularity based on various features.

## Tools and Technologies Used
- Python for data collection and processing.
- Spotify API for accessing music data.
- Pandas and NumPy for data manipulation.
- Matplotlib and Seaborn for data visualization.
- Sci-kit Learn for predictive modeling.

## How to Use this Repository
1. **Data Collection Scripts**: Navigate to the `scripts` directory to find the Python code used for data extraction.
2. **Data**: The `data` directory contains the merged dataset in CSV format.
3. **Notebooks**: Jupyter notebooks with detailed analysis and visualizations are located in the `notebooks` directory.
4. **Models**: The `models` directory contains the serialized models used for predicting song popularity.

## Conclusion
By examining this dataset, we will gain valuable insights into the dynamics of music popularity. These insights can guide decision-making in the music industry and enhance our understanding of music consumption patterns on streaming platforms.
