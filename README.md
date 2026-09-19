# Song Recommendation System Using Content-Based Filtering

A content-based song recommendation system that recommends similar songs based on Spotify audio features and metadata. The project applies exploratory data analysis (EDA), data preprocessing, and cosine similarity to generate song recommendations.

## Highlights

- Exploratory data analysis of song metadata and audio features
- Data cleaning, duplicate removal, and missing value imputation
- Feature engineering using release year
- Audio feature scaling using RobustScaler
- Song similarity calculation using cosine similarity
- Content-based recommendation system
- Recommendation results based on song titles

## Data

The dataset contains 4,999 song records and 19 columns, including:
- Song and artist information
- Album details and release date
- Popularity
- Spotify audio features such as danceability, energy, loudness, acousticness, and valence

## Method

The recommendation system follows these steps:
1. Clean and preprocess the dataset
2. Remove duplicate tracks based on Track URI
3. Handle missing values using categorical and numerical imputation
4. Select relevant audio features
5. Scale features using RobustScaler
6. Calculate song similarity using cosine similarity
7. Recommend songs with similar audio characteristics

## How to Run

The notebook was developed using Python and Jupyter Notebook.

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/song-recommendation.git
