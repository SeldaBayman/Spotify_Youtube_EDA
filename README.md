# Spotify_Youtube_EDA DataSet Information:
The dataset consists of songs from various artists worldwide, and for each song, it includes: various statistics from the music release on Spotify, 
including the number of streams; and the view count of the official music video on YouTube."

![Spotify_1](https://github.com/user-attachments/assets/5d931578-e434-4350-a0fb-0a60ee7e5ca8)

Spotify Columns:
track_name: Name of the song or track.
artist_name: Name of the artist or band who performed the track.
album_name: The album to which the track belongs.
popularity: Spotify's calculated popularity score for the track (0-100).
release_date: Date when the track or album was released.
duration_ms: Length of the track in milliseconds.
danceability: Measure of how suitable a track is for dancing, ranging from 0.0 to 1.0.
energy: A measure from 0.0 to 1.0 representing the intensity and activity of the track.
key: The musical key in which the track is composed (0 = C, 1 = C♯/D♭, and so on).
loudness: Average loudness of the track in decibels (dB).
mode: Indicates whether the track is in a major (1) or minor (0) key.
speechiness: Amount of spoken words in a track, ranging from 0.0 to 1.0.
acousticness: Confidence measure from 0.0 to 1.0 of whether the track is acoustic.
instrumentalness: Predicts whether a track contains no vocals. A higher value means the track is more instrumental.
liveness: Detects the presence of an audience in the recording. Higher values indicate more "live" performance.
valence: Describes the musical positiveness of a track. Tracks with high valence sound more positive (happy, cheerful), and tracks with low valence sound more negative (sad, angry).
tempo: The overall speed or pace of the track in beats per minute (BPM).

YouTube Columns:

video_id: Unique identifier for each YouTube video.
title: Title of the YouTube video.
channel_name: Name of the channel that uploaded the video.
category: Video category assigned by YouTube (e.g., Music, Entertainment, Education).
views: The total number of views the video has received.
likes: The total number of likes on the video.
duration: Length of the video in minutes or seconds.
tags: Keywords associated with the video for search optimization.
thumbnail_link: Link to the thumbnail image of the video.
description: Text description provided by the uploader to describe the video.


Project Title:
Exploratory Data Analysis (EDA) of Spotify and YouTube with Python

Introduction:
In this project, I performed an exploratory data analysis (EDA) of Spotify and YouTube datasets using Python. The goal was to extract insights into music streaming behavior and video content trends, comparing user preferences, engagement metrics, and platform dynamics.

Dataset Description:
The Spotify dataset contains information such as track names, artists, popularity, and audio features (e.g., danceability, energy). The YouTube dataset includes video titles, channel information, view counts, likes, dislikes, and engagement metrics. Both datasets allow us to analyze content characteristics and how they influence user interaction.

Tools and Libraries Used:
Python: pandas, numpy, matplotlib, seaborn, plotly
Jupyter Notebook for analysis and visualization

Key Analysis and Insights:
Spotify Music Trends:
Popular genres and artists over time
Audio features like energy and danceability correlated with track popularity
Distribution of track lengths and their popularity impact

YouTube Content Insights:
Top video categories and creators with highest engagement
Correlation between video views, likes, and dislikes
Analysis of video upload frequency and its impact on channel growth.
![Phyton_8](https://github.com/user-attachments/assets/00364314-c664-4f63-ad35-73cc21bd7755)

Cross-Platform Comparisons:
Comparing content engagement patterns between audio (Spotify) and video (YouTube)
Examining how content consumption behaviors differ between music listeners and video viewers

![Phyton_1](https://github.com/user-attachments/assets/b5067f93-7e45-4bec-95bc-b25f2ad24d61)


Conclusion:
This EDA provided a detailed comparison of user engagement across two leading digital platforms. 
It highlights key factors that contribute to content success, offering valuable insights for content creators and digital marketers.
