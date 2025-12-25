# Amazon Prime Video Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Amazon Prime
Video dataset to understand content distribution, trends, viewer engagement,
and production patterns across movies and TV shows available on the platform.

The analysis focuses on identifying insights related to content type, genres,
ratings, runtime, seasons, release trends, and production countries using
Python-based data analysis and visualization techniques.

---

## 🎯 Objectives
- Analyze the distribution of Movies and TV Shows on Amazon Prime Video
- Explore dominant genres and content diversity
- Study trends in runtime, seasons, and release years
- Understand viewer engagement using IMDb and TMDb ratings
- Examine regional contributions to the content library

---

## 📂 Dataset Description
The project uses two datasets:
- **titles.csv** – Contains metadata about movies and TV shows such as title,
  type, genres, release year, runtime, ratings, and popularity metrics.
- **credits.csv** – Includes information about cast and crew associated with
  each title.

Both datasets are merged using a common identifier (`id`) to form a unified
dataset for analysis.

---

## 🧹 Data Preprocessing
The following preprocessing steps were applied:
- Merged titles and credits datasets using the `id` column
- Removed records with missing values in critical columns such as
  `description` and `imdb_id`
- Replaced missing categorical values using logical defaults:
  - `age_certification` → mode
  - `character` → "unknown"
- Handled numerical missing values using appropriate strategies:
  - `seasons`, `imdb_votes` → 0
  - `imdb_score`, `tmdb_score`, `tmdb_popularity` → mean values
- Removed duplicate records to ensure data consistency

---

## 📊 Exploratory Data Analysis
The analysis includes a wide range of visualizations:
- **Box plots** to identify distributions and outliers
- **Histograms** to study numerical distributions
- **Bar and count plots** for categorical comparisons
- **Scatter plots** to observe relationships between ratings and votes
- **Line plots** to analyze trends over time
- **Pie charts** for proportion-based insights
- **Violin plots** to compare rating distributions
- **Pair plots and heatmaps** to examine correlations among numerical features

---

## 🔍 Key Insights
- Movies dominate the Amazon Prime Video content catalog compared to TV shows
- Drama and Comedy are the most common genres on the platform
- Average movie runtime has slightly decreased over time, while TV shows have
  increased in number of seasons
- Older titles tend to receive higher IMDb and TMDb ratings than newer ones
- Content production is led by the United States, followed by India and the
  United Kingdom
- Viewer engagement is positively correlated with the number of IMDb votes

---

## 🛠️ Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Plotly
- Jupyter Notebook / Google Colab

---

## 📈 Conclusion
This EDA provides a comprehensive understanding of Amazon Prime Video’s content
landscape and evolving trends. The insights can support content creators,
platform strategists, and analysts in making data-driven decisions. Further
extensions may include genre-specific analysis, cross-platform comparisons,
or building recommendation systems.

---

## 👤 Author
**Sanjay**  
B.Tech CSE, IIT Patna
