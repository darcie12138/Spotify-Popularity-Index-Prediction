# Regression and Neural Network Analysis for Spotify Popularity Prediction

This project predicts Spotify track popularity using a combination of regression, random forest, and neural network models. The analysis involves data scraping, feature engineering, and advanced machine learning techniques.

## Overview

The primary goal of this project is to analyze the key factors influencing the Spotify popularity score and build predictive models. Key highlights include:
- Data scraping using `BeautifulSoup` and Spotify API for over 10,000 songs.
- Feature extraction from audio embeddings with YAMNet.
- Implementation of regression, random forest, and neural network models for analysis.

## Key Features
- **Data Collection**: Web scraping and API integration to gather song metadata and features.
- **Modeling**:
  - Regression models to understand basic relationships.
  - Random forest for feature importance and non-linear patterns.
  - Neural networks using TensorFlow and Keras to achieve improved accuracy.
- **Audio Feature Analysis**: Leveraged 521-dimensional audio embeddings from YAMNet for richer data representation.

## Tools and Technologies
- **Python Libraries**: Pandas, BeautifulSoup, Scikit-learn, TensorFlow, Keras.
- **APIs**: Spotify API, Last.fm API.
- **Audio Analysis**: YAMNet.

## Results
- Improved prediction accuracy with neural networks, achieving an R² of 0.5 compared to initial regression models (R² = 0.0022).
- Insights into the influence of audio features, streaming metrics, and genres on Spotify popularity scores.
