# Sportify-EDA-project---Code-Alpha
Analysis of a sportify data set to give insights and analysis 
# 🎵 Spotify Market Analysis & EDA

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on a dataset of Spotify tracks to uncover market trends, genre dominance, and the characteristics of popular music. 

Using **Python (Pandas, Seaborn, Matplotlib)**, we analyzed the relationship between song duration, explicit content, and popularity scores to understand what makes a song successful on the platform.

## 📊 Dataset
**Source:** [Kaggle - Spotify Dataset](https://www.kaggle.com/datasets/ambaliyagati/spotify-dataset-for-playing-around-with-sql)
The dataset contains track information including:
- **Market Data:** Popularity scores, Genre, Artist.
- **Track Features:** Duration (ms), Explicit content flag.


Key Insights
1. The "Balanced" Nature of the Data
Our analysis revealed that the dataset is perfectly stratified, with an equal number of tracks sampled per genre (approx. 50 tracks each). This prevents genre bias when performing further statistical analysis or machine learning modeling.

2. The "Hit Song" Rarity
The popularity distribution (Histogram) shows a right-skewed trend:

A significant portion of tracks have a Popularity Score of 0 (obscure or older tracks).

The majority of "active" songs sit in the 20–60 range.

Super Hits (90+) are statistically rare, confirming that achieving viral status is an outlier event.

3. Explicit Content vs. Popularity
Visual analysis suggests that while explicit songs make up a smaller portion of the total library, they often maintain a slightly higher median popularity compared to non-explicit tracks, likely driven by modern Pop and Hip-Hop trends.

🛠️ Tech Stack
Python: Core logic

Pandas: Data cleaning and manipulation

Seaborn & Matplotlib: Data visualization

Jupyter Notebook: Interactive analysis environment

