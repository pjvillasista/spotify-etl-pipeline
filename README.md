# Project Title: Global Music Trends: Analyzing Spotify's Top 50 Playlist

## Introduction
This project delves into the evolving landscape of global music preferences by analyzing Spotify's Top 50 - Global playlist. The goal is to identify what characteristics make a track successful on a worldwide scale and to uncover patterns in music that resonate across diverse cultures.

## Problem Statement
The music industry is highly dynamic, with global hits emerging from various regions and genres. Understanding the attributes that contribute to a song's success can provide artists, producers, and labels with actionable insights to craft future hits. This project focuses on deciphering the commonalities among the tracks that make it to Spotify's Top 50 - Global playlist.

## Data Collection
Data was meticulously extracted from Spotify's API, focusing on the Top 50 - Global playlist. The dataset includes:

- **Album Data**: Information about the album of each track, such as IDs, names, release dates, and more.
- **Artist Information**: Artist genres, popularity scores, followers, and images.
- **Song Details**: Track-specific data, including IDs, names, popularity, explicitness, and other relevant metrics.
- **Audio Features**: Technical attributes of each track, such as danceability, tempo, and mood indicators.

Python scripts were written to query the Spotify API and process the data into a structured form for subsequent analysis.

## Data Processing
The gathered data were consolidated into a singular CSV file, creating an extensive dataset that captures the essence of the current global music trends. This merged data allows for a comprehensive analysis of the various aspects affecting a track's performance.

## Analysis
Key areas of analysis will include:

- **Temporal Popularity Trends**: Examining how the popularity of tracks fluctuates over time.
- **Success Attributes**: Identifying song features that are commonly seen in top-charting tracks.
- **Cross-Cultural Appeal**: Understanding the elements that give a song universal appeal across different regions.
- **Genre Popularity**: Analyzing the representation and performance of various genres in the global top charts.
- **Predictive Insights**: Using machine learning to predict potential future hits based on their attributes.

## Tools and Technologies Used
- Python for scripting and data processing.
- Spotify API for data acquisition.
- Data analysis libraries: Pandas, NumPy.
- Visualization libraries: Matplotlib, Seaborn.
- Machine learning libraries: Sci-kit Learn for building predictive models.

## Repository Structure
1. **Scripts**: Contains Python scripts for data collection (`data_collection/`).
2. **Data**: Merged dataset in CSV format located in the `data/` directory.
3. **Analysis**: Jupyter notebooks with exploratory data analysis in the `analysis/` directory.
4. **Models**: Machine learning models are stored in the `models/` directory.

## Conclusion
The insights from this analysis will shed light on the factors that drive a song to international success, allowing stakeholders in the music industry to make data-driven decisions.
