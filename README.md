# 🎵 Spotify Data Analysis with Python

## 📌 Project Overview

This project analyzes Spotify music data using Python to uncover insights about song characteristics, artist performance, genre trends, and listener preferences. Through Exploratory Data Analysis (EDA), correlation analysis, and interactive visualizations, the project identifies patterns that influence song popularity and evolving music trends.

The objective is to provide **data-driven insights** that can help music producers, marketers, and playlist curators make informed decisions.

---

## 🎯 Project Objectives

- Analyze relationships between song features and popularity
- Identify trends in music attributes over time
- Discover top-performing genres and artists
- Provide actionable business recommendations
- Create interactive visualizations for deeper exploration

---

## 📂 Dataset Information

The dataset includes Spotify track metadata such as:

- Song Name
- Artist
- Genre
- Popularity
- Danceability
- Energy
- Tempo (BPM)
- Acousticness
- Loudness (dB)
- Valence
- Release Date
- Duration

Data Source: Spotify API / Public Spotify datasets

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Google Colab

---

## 🔎 Project Workflow

### 1️⃣ Data Preparation

- Loaded datasets (`artists.csv`, `tracks.csv`)
- Removed duplicates
- Handled missing values using median imputation
- Converted release dates to datetime format
- Extracted release year
- Created new features:
  - Popularity category (Low / Medium / High)
  - Duration in minutes
- Normalized selected features using MinMaxScaler

---

### 2️⃣ Exploratory Data Analysis (EDA)

- Descriptive statistics
- Correlation heatmap
- Feature distributions
- Outlier detection (boxplots)
- Bivariate analysis (scatter plots)

Key questions explored:
- Does danceability affect popularity?
- Is energy correlated with tempo?
- Are louder songs more popular?

---

### 3️⃣ Data Visualization

Visualizations created:

- Histogram (feature distribution)
- Bar charts (top songs / genres)
- Scatter plots (energy vs popularity)
- Boxplots (outlier detection)
- Heatmap (correlation analysis)
- Time-series trends (popularity over years)
- Interactive Plotly visualizations

---

### 4️⃣ Musical Trend Analysis

- Popularity trends over time
- Danceability and energy evolution
- Genre growth patterns
- Artist performance trends

---

## 📊 Key Insights

- Highly popular songs tend to have:
  - Higher energy
  - Higher danceability
  - Moderate tempo
- Loudness shows a positive correlation with popularity.
- Recent music trends show increasing energy levels.
- Certain genres consistently dominate streaming platforms.

---

## 💡 Business Recommendations

- Invest in producing high-energy, danceable tracks.
- Create mood-based playlists using feature thresholds.
- Use trend analysis for targeted music marketing.
- Monitor emerging genre shifts for early adoption strategies.

---

## 📁 Project Structure

```
Spotify-Data-Analysis/
│
├── data/
│   ├── artists.csv
│   └── tracks.csv
│
├── notebook/
│   └── spotify_analysis.ipynb
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository:
```
git clone https://github.com/yourusername/spotify-data-analysis.git
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Open the notebook in Google Colab or Jupyter:
```
spotify_analysis.ipynb
```

---

## 📈 Future Improvements

- Add Machine Learning model to predict song popularity
- Build Streamlit dashboard
- Deploy interactive web app
- Perform clustering analysis for playlist segmentation
- Use NLP on song lyrics for sentiment analysis

---

## 👤 Author

Manoj M Holagi  
Data Analyst | Python | SQL | Machine Learning  

---

## ⭐ If You Like This Project

Give this repository a ⭐ and feel free to fork or contribute!

