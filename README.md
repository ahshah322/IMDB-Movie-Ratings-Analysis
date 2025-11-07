# 🎬 IMDB Movie Ratings Analysis

A clean and well-structured **data analysis project** exploring **IMDB Top 250 Movies** data using **Python, Pandas, NumPy, Seaborn, and Matplotlib**.  
This notebook reveals insights into movie ratings, genres, budgets, box office collections, runtimes, and directors — all presented through clear, engaging visualizations.

---

## 🔍 Project Overview

This project aims to analyze patterns and relationships in IMDB movie data.  
Through data cleaning, transformation, and visualization, it helps answer questions such as:

- Which movies have the highest ratings?  
- Which genres and directors are most popular?  
- How do budget and box office earnings relate?  
- Is there a correlation between runtime and rating?  
- What are the most common certificate categories?

Each step is written to be **beginner-friendly** and reproducible in **Google Colab** or **Jupyter Notebook**.

---

## 🧭 Notebook Outline

1. **Introduction** – Overview of goals and dataset.  
2. **Imports & Display Settings** – Load libraries and set visual themes.  
3. **Load & Preview Data** – Import and inspect the dataset.  
4. **Helper Cleaning Functions** – Convert runtime and money formats into numeric types.  
5. **Apply Cleaning & Normalize Columns** – Standardize data types and extract key features.  
6. **Drop Incomplete Records** – Remove rows with missing essential data.  
7. **Analysis 1:** Top 10 Movies by Rating (Horizontal Bar)  
8. **Analysis 2:** Distribution of Ratings (Histogram + KDE)  
9. **Analysis 3:** Top Years with Most Movies (Vertical Bar)  
10. **Analysis 4:** Rating Distribution by Genre (Boxplot)  
11. **Analysis 5:** Budget vs Box Office (Scatter with Log Scale)  
12. **Analysis 6:** Runtime vs Rating (Scatter + Regression)  
13. **Analysis 7:** Top Directors by Number of Movies (Horizontal Bar)  
14. **Analysis 8:** Correlation Heatmap (Numeric Features)  
15. **Analysis 9:** Certificate Distribution (Pie Chart)
16. **Conclusions** Compact interpretation.

---

## ⚙️ Features

- Comprehensive **data cleaning** and transformation.  
- Visual exploration with **9 key analyses**.  
- Helper functions for parsing **monetary** and **runtime** values.  
- Insights on relationships between **budget, revenue, and ratings**.  
- Ready-to-run on **Google Colab**.

---

## 🧾 Dataset

The notebook expects a CSV file named `movies.csv` with the following columns:

| Column Name | Description |
|--------------|-------------|
| rank | IMDB ranking number |
| name | Movie title *(required)* |
| year | Release year |
| rating | IMDB rating |
| genre | Comma-separated genres |
| certificate | Film classification (e.g., PG, R, G) |
| run_time | e.g., `2h 22min` or `142 min` |
| tagline | Short tagline (if available) |
| budget | e.g., `$12M`, `€300K` |
| box_office | e.g., `$100M`, `£500K` |
| casts | Main cast members |
| directors | Comma-separated names |
| writers | Comma-separated names |

📝 *If your CSV filename or path differs, update it in the `pd.read_csv()` function.*

---

## ▶️ How to Run (Google Colab)

1. Open the notebook [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ahshah322/IMDB-Movie-Ratings-Analysis/blob/main/notebooks/IMDB_Movie_Ratings_Analysis.ipynb)
2. Upload your `movies.csv` file to Colab’s `/content/` directory.
3. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
4. Run all cells sequentially.  
5. View the output charts and insights directly in Colab.

---

## 💡 Key Visualizations

- Top 10 Movies by Rating
- Rating Distribution (Histogram + KDE)
- Top Years for Movie Releases
- Genre-wise Rating Boxplot
- Budget vs Box Office (Scatter + Regression)
- Runtime vs Rating (Regression Plot)
- Top Directors by Number of Movies
- Numeric Correlation Heatmap
- Certificate Distribution Pie Chart

Each visualization provides valuable insights into movie data patterns.

---

## 📈 Example Insights

- Most highly rated movies come from Drama and Action genres.
- Budgets and box office earnings show a moderate positive correlation.
- Longer movies tend to have slightly higher ratings.
- Certain directors dominate the top movie list.
- The majority of movies fall into a few key certificate categories.

---

### 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

### 👨‍💻 Author

**Ali Husnain Shah**

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=plastic&logo=gmail&logoColor=white)](mailto:a.h.shah322@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-000?style=plastic&logo=github&logoColor=white)](https://github.com/ahshah322)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=plastic&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahshah322)
