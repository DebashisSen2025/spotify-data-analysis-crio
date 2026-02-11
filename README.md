## Spotify Data Analysis using Python 🎵📊

## Author
**Debashis Sen**

## Project Overview
This project performs Exploratory Data Analysis (EDA) and Data Visualization on Spotify datasets to uncover trends in music popularity, audio features, and genre dominance.

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key Analysis Performed
- Top 10 most popular & least popular songs
- Correlation heatmap of audio features
- Regression analysis (Energy vs Loudness)
- Popularity trends over years
- Genre dominance comparison (Top Hits vs All Tracks)
- Pop genre deep analysis

## Dataset
Spotify dataset files:
- tracks.csv
- artists.csv
- ## 📁 Dataset

Download the dataset from Google Drive:

👉 [Spotify Dataset (Download)](https://drive.google.com/file/d/1YtYpHPsIPjBKDyndwibncC69_iUTfAy2/view?usp=drive_link)

After downloading, use direct download in your script like:

```python
import pandas as pd

url = "https://drive.google.com/uc?export=download&id=1YtYpHPsIPjBKDyndwibncC69_iUTfAy2"
tracks = pd.read_csv(url)


## How to Run
1. Clone repository
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
