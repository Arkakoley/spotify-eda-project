# spotify-eda-project
"An exploratory data analysis of Spotify tracks to uncover trends in music popularity."
%%writefile README.md
# Spotify Tracks EDA Project 🎵

## Overview
This project performs an **Exploratory Data Analysis (EDA)** on a dataset of Spotify tracks.  
The goal is to understand how different audio features (like danceability, energy, loudness, tempo, valence, etc.) relate to a track’s **popularity** and how these characteristics have changed over time.

## Files in this Repository
- `Spotify_EDA.ipynb` → Main Jupyter Notebook containing all code, visualizations, and insights  
- `report.pdf` → Written summary of analysis and results  
- `README.md` → Project overview and usage instructions  
- `spotify.csv` → Dataset file (if allowed to upload)

## Setup Instructions
1. Open the notebook in **Google Colab**.
2. Upload the dataset `spotify_tracks.csv` or mount Google Drive.
3. Run all cells sequentially.
4. All plots and insights will be generated automatically.

## Key Analyses Performed
- **Univariate analysis:** distributions of popularity, danceability, energy, etc.  
- **Bivariate analysis:** relationships such as danceability vs popularity, energy vs valence.  
- **Correlation heatmap:** to identify strongest relationships between features.  
- **Time-series trends:** how song characteristics evolved over years.  
- **Recommendations:** insights for music producers or mixing engineers.

## Tools Used
- Python 3  
- pandas, numpy, matplotlib, seaborn, scikit-learn  

## Insights Summary
- Highly popular songs tend to have **high danceability & energy**.  
- **Average loudness has increased** while **song duration decreased** over the years.  
- Songs in multiple languages (like Spanish & Korean) show rising popularity trends.

## Author
*ARKA KOLEY*  
Data Science Student – Spotify EDA Project
