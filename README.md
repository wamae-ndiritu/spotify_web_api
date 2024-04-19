# Taylor Swift Sentiment Analysis

This project aims to analyze the sentiment of Taylor Swift's songs using the Spotify Web API and perform various visualizations and analyses based on the retrieved data.

## Overview

The project involves the following steps:

1. **Dataset Creation**: A CSV file named `top_bottom_taylor_songs.csv` was created containing the top and bottom 10 streamed songs by Taylor Swift. The dataset includes song details such as name, album, artist, streams, and category (top or bottom).

2. **Data Cleaning**: The dataset was cleaned by checking for null values and duplicates.

3. **Spotify Developer Account**: A Spotify Developer Account was created, and a demo application was registered to provide authentication and access to the Spotify Web API. The generated CLIENT ID and CLIENT SECRET were used to obtain an access token.

4. **Data Retrieval**: The Spotify Web API was used to access track details for each song in the dataset. Details extracted include track name, artist name, album name, count of market availability, track duration, explicitness, popularity, and locality.

5. **Data Analysis**: Various visualizations and analyses were performed using the extracted song data. This includes sentiment analysis, comparison between top and bottom streamed songs, and visualization of streams across release time.

## Files

- `top_bottom_taylor_songs.csv`: Dataset containing the top and bottom streamed songs by Taylor Swift.
- `extracted_songs_data.csv`: Dataset containing extracted song details retrieved from the Spotify Web API.
- `Taylor Swift Sentiment Analysis.ipynb`: Jupyter Notebook containing the code for data retrieval, cleaning, analysis, and visualization.

## Dependencies

- Python 3.x
- pandas
- spotipy
- matplotlib
- seaborn


