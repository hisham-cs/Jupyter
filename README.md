# 🎬 IMDB Top 250 Movies Analysis

Exploratory data analysis of the **IMDB Top 250 Movies** dataset using **Pandas** and **Matplotlib**.  
This project was built as a practice exercise.

---

## 📊 Dataset

- Source: [Kaggle](https://www.kaggle.com/)  
- Content: Top 250 movies of all time on IMDB, including:
  - `Rank` – movie rank in Top 250  
  - `Title` – movie title  
  - `Release` – release year  
  - `Runtime` – duration in text format like `"2h 22m"`  
  - `Rated` – rating category (R, PG-13, PG, …)  
  - `Ratings` – IMDB rating (float)

---

## 📝 Project Steps

**Step 0 — Setup**  
- Import libraries and load dataset.

**Step 1 — Data Preparation**  
- Convert `Runtime` into numeric minutes (`RuntimeMinutes`).  
- Create a `Decade` column from `Release`.

**Step 2 — Top 10 Movies by Rating**  
- Sort by `Ratings` and display the 10 highest-rated movies.

**Step 3 — Movies by Decade**  
- Count movies per decade and plot a bar chart.

**Step 4 — Runtime & Rating Categories**  
- Histogram of runtimes.  
- Average runtime, longest and shortest movies.  
- Distribution of rating categories.  
- Average rating per decade (table).

**Step 5 — Conclusion**  
- Summarize insights from the analysis.

---

## 📌 Key Results

- **Highest-rated movie:** *The Shawshank Redemption*  
- **Average runtime:** ~129.8 minutes  
- **Longest movie:** *Gone with the Wind* (1939) — 3h 58m, rating 8.2  
- **Shortest movie:** *Sherlock Jr.* (1924) — 45m, rating 8.2  
- **Decade with most movies:** 2000s (48 titles)  
- **Average rating by decade:**

  | Decade | Avg. Rating |
  |-------:|------------:|
  | 1920 | 8.17 |
  | 1930 | 8.28 |
  | 1940 | 8.26 |
  | 1950 | 8.28 |
  | 1960 | 8.34 |
  | 1970 | 8.35 |
  | 1980 | 8.28 |
  | 1990 | 8.40 |
  | 2000 | 8.30 |
  | 2010 | 8.25 |
  | 2020 | **8.41** |

  > Note: Although the 2020s have the highest average rating (8.41),  
  > the number of movies is relatively small. The 1990s (8.40) are nearly equal in quality but with more films.

- **Most common rating category:** **R**

---


## Repository Contents
- **imdb-analysis.ipynb** → Jupyter Notebook that contains all the analysis steps, plots, and conclusions.  
- **IMDB_processed_data.csv** → The dataset used for the analysis, downloaded from Kaggle.






