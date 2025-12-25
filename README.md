# Amazon Prime Video Content Analysis

## Overview
This project explores the content available on Amazon Prime Video using
Exploratory Data Analysis (EDA). The objective is to understand how movies
and TV shows are distributed across genres, years, ratings, and popularity
metrics.

Instead of focusing only on descriptive statistics, this analysis emphasizes
content trends and platform-level observations.

## Dataset Description
The analysis is based on two datasets:
- Titles information (movies and TV shows)
- Credits information (cast and crew)

These datasets were combined using a common content identifier.

## Key Questions Explored
- How is Amazon Prime’s catalog split between movies and TV shows?
- Which genres dominate the platform?
- How has content production evolved over the years?
- Is there a visible relationship between IMDb ratings and audience votes?

## Data Preparation
The following preprocessing steps were performed:
- Removal of rows with missing critical identifiers
- Imputation of missing numerical values using statistical measures
- Standardization of categorical fields
- Elimination of duplicate records

## Visual Analysis
The project includes:
- Distribution plots for ratings and release years
- Genre frequency analysis
- Trend analysis across time
- Popularity vs rating comparisons

## Observations
The analysis shows that Amazon Prime focuses heavily on certain genres and
has increased content production significantly after 2015. Higher IMDb
votes generally correlate with stable rating values, indicating consistent
viewer engagement.

## Tools Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

## Future Scope
- Comparison with other OTT platforms
- Sentiment analysis using reviews
- Recommendation system experiments
