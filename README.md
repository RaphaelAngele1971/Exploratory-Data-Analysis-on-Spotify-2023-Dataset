# 🎧 Analyzing Spotify’s Most Streamed Songs of 2023 🎧

This repository showcases an **Exploratory Data Analysis (EDA)** of the Most Streamed Spotify Songs in 2023. The goal of this analysis is to examine a dataset of popular tracks on Spotify, revealing trends, patterns, and connections that define songs with high streaming numbers. By utilizing data visualization and statistical methods, this research seeks to discover insights regarding track popularity, investigating elements such as musical features, timing of release, and the presence of artists that might influence a song's success.

**Dataset:** [Most Streamed Spotify Songs 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023) on Kaggle

## 📊 Overview

The goal of this analysis is to gain meaningful insights from the dataset by analyzing, visualizing, and interpreting the data. We’ll explore the relationship between streaming counts, musical attributes, and artist popularity, and reveal what may contribute to a song’s success.

## 📜 General Guidelines

To get the best insights from our analysis, we’ll follow these steps:

1. **Dataset Familiarization**  
   - Start by checking the dataset's structure, including **missing values** and **data types**.
   - Perform an initial exploration to understand each feature and how they contribute to track popularity.

2. **Summary Statistics**  
   - Compute summary statistics (mean, median, standard deviation) for key metrics like **streams** and **release dates**.
   - Look into musical attributes such as **BPM** and **danceability**.

3. **Data Visualization**  
   - Use **bar charts**, **histograms**, and **scatter plots** to uncover trends and patterns.
   - Ensure all visualizations are well-labeled and clear.

4. **Correlation Analysis**  
   - Examine correlations between variables like **streams** and **BPM** or **energy**.
   - Interpret these findings to understand relationships and patterns in musical characteristics.

5. **Insights and Recommendations**  
   - Based on the analysis, suggest insights about the tracks, artists, and trends that make songs popular.

## ❓ Guide Questions

Throughout the analysis, address the following questions:

### 🔍 Overview of Dataset

- How many rows and columns does the dataset contain?
- What are the data types of each column? Are there any missing values?

### 📈 Basic Descriptive Statistics

- What are the mean, median, and standard deviation of the `streams` column?
- What is the distribution of `released_year` and `artist_count`? Are there any noticeable trends or outliers?

### 🎤 Top Performers

- Which track has the highest number of streams? Display the top 5 most streamed tracks.
- Who are the top 5 most frequent artists in the dataset?

### ⏳ Temporal Trends

- Analyze the trend in track releases over time. Plot the number of tracks released per year.
- Do track releases show any monthly patterns? Which month sees the most releases?

### 🎼 Genre and Music Characteristics

- Examine the correlation between streams and musical attributes like `bpm`, `danceability_%`, and `energy_%`. Which attributes influence streams the most?
- Is there a correlation between `danceability_%` and `energy_%`? Also, check correlations between `valence_%` and `acousticness_%`.

### 📊 Platform Popularity

- How do the counts of tracks in `spotify_playlists`, `spotify_charts`, and `apple_playlists` compare? Which platform favors the most popular tracks?

### 🔍 Advanced Analysis

- Are there any patterns among tracks with the same key or mode (Major vs. Minor)?
- Do certain genres or artists consistently appear in more playlists or charts? Compare the most frequently appearing artists across playlists and charts.

## 🖥️ IDE & Setup

### 💡 IDE
- **IDE**: You can use any Python-based IDE for this project, but the one used by the author is:
  - **Jupyter Notebook** (ideal for interactive exploration)

### 📚 Libraries
This project uses the following Python libraries:
- **Pandas** - For data manipulation and analysis
- **Matplotlib** - For creating static, animated, and interactive visualizations
- **Seaborn** - For statistical data visualization based on Matplotlib

> [!IMPORTANT]
> ## 📌 Notes
>
> - Ensure that your code is **clean, well-commented, and organized**.
> - Use **Python libraries** such as pandas for data manipulation and matplotlib or seaborn for visualization.
> - Provide a **brief written interpretation** of each key insight you discover.

## 👤 Author
- Name: AFIDCHAO, Danielle Taylan
- Section: 2ECE-A
- Github: [RaphaelAngele1971](https://github.com/RaphaelAngele1971)

> [!IMPORTANT]
> ## DEADLINE: November 09, 2024
