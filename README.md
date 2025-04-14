# Netflix_analyze

# 📊 Netflix Dataset Exploratory Data Analysis (EDA)

![Netflix](https://img.shields.io/badge/Netflix-EDA-red) ![Python](https://img.shields.io/badge/Python-3.9-blue) ![License](https://img.shields.io/badge/License-MIT-green)

This project dives deep into the Netflix Movies and TV Shows dataset using Python, Pandas, Matplotlib, and Seaborn. We aim to extract meaningful insights from the content metadata, understand trends, and visualize the evolution of Netflix’s content catalog.

---

## 📁 Dataset Overview

- Source: Netflix Titles from Kaggle
- Rows: ~8800
- Columns: 12
- Features: Type, Title, Cast, Country, Rating, Duration, Release Year, etc.

---

## 🧰 Tools & Libraries

- Python (v3.9+)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Key Objectives

- Clean and preprocess the dataset
- Perform visual & statistical exploration
- Understand content distribution by type, rating, and release year
- Derive insights to inform content strategy

---

## 📊 Visualizations & Insights

| Visualization | Insight |
|---------------|---------|
| 📺 Type Distribution (`countplot`) | Netflix has significantly more Movies than TV Shows. |
| 🎬 Ratings Distribution | Most content is rated ‘TV-MA’ or ‘TV-14’, indicating mature audience focus. |
| 🗓️ Release Year Histogram | Content releases peaked between 2018–2020, indicating a growth phase. |
| ⏳ Duration Comparison | Movies average around 90 minutes. TV Shows often range from 1–3 seasons. |
| 🌍 Country of Origin | USA dominates content production, followed by India, UK, and Canada. |
| 🔥 Correlation Heatmap | Minimal correlation between duration and release year. |
| 🧮 Pairplot | Clear visual separation of Movies vs TV Shows on duration. |

---

## 📁 Folder Structure

```bash
Netflix-EDA/
│
├── netflix_titles.csv         # Original dataset
├── Netflix_EDA.ipynb          # Jupyter Notebook with full analysis
├── images/                    # Visualizations (optional)
├── README.md                  # Project documentation
└── requirements.txt           # Libraries used
