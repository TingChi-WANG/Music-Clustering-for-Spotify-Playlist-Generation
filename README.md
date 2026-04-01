# Music-Clustering-for-Spotify-Playlist-Generation
This project aims to optimize Spotify's automated playlist curation by using song audio features to group tracks into specific mood or activity-based playlists. We analyzed a Spotify tracks dataset, cleaned it, and applied K-Means clustering (with K=3) to categorize songs based on features like danceability, energy, and acousticness. Through PCA-driven visualizations and a radar chart, we successfully identified three distinct musical profiles: "Acoustic & Chill," "Upbeat Party Hits," and "Intense & Heavy Beats." This segmentation provides a robust foundation for improving music recommendation systems.

**Business Problems (Marketing Analytics)**
How can song audio features (such as danceability, energy, valence, tempo) be used to automatically group songs to match specific moods or activities (e.g., 'workout', 'relax', 'party' playlists)

**Objectives**
Improve the recommendation quality of algorithmic playlists and user experience

**Dataset**
Spotify Tracks Dataset from Kaggle
https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset 
-  Dataset Size: The dataset contains 114,000 observations (rows; songs) and 21 variables (columns; variables describing each song).
-  Data Types:
  -   Numerical (int64 / float64): popularity, duration_ms, danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, time_signature
  -  Categorical / Text (object): track_id, artists, album_name, track_name, track_genre
  -  Boolean: explicit
  -  Irrelevant / Index-like column: Unnamed: 0
