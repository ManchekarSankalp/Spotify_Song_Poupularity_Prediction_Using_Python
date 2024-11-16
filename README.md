Spotify Data Analysis and Visualization
This repository contains a data science project analyzing Spotify's music dataset. The project explores various attributes of tracks, including popularity, duration, danceability, and energy, and applies statistical methods, visualizations, and machine learning techniques.

Features
Data Analysis and Cleaning:

Inspect and preprocess Spotify's music dataset (Spotify_Dataset.csv).
Handle missing and duplicate values.
Convert data types and rename columns for clarity.
Data Visualization:

Generate box plots, histograms, scatter plots, bar plots, and pie charts.
Correlation analysis with a heatmap.
Understand the distribution and relationships among various features.
Machine Learning:

Predict "danceability" using a linear regression model.
Evaluate model performance with metrics: Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2).
Cluster tracks using K-Means clustering and visualize clusters with PCA.
Libraries Used:

pandas, numpy for data manipulation.
matplotlib, seaborn for visualizations.
scikit-learn for machine learning.
Dataset
The dataset (Spotify_Dataset.csv) contains information on 114,000 tracks, including:

Categorical Attributes: artists, album_name, track_name, track_genre.
Numerical Attributes: popularity, duration_ms, danceability, energy, key, tempo, etc.

Results
Linear regression achieved a Mean Squared Error (MSE) of 0.026 and an R-squared (R2) of 0.124.
Clusters of songs were visualized in 2D space using PCA.
Future Work
Enhance predictive models with advanced machine learning techniques.
Explore more features for clustering and dimensionality reduction.
