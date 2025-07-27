# 🎬 IMDb Movies Data Analysis Project (SQL + Python + Power BI)

This project presents a complete data analysis workflow using IMDb movie data, integrating **SQL**, **Python (Pandas)**, and **Power BI** to uncover insights about global movie performance, audience preferences, financial trends, and genre dynamics.

---

## 📌 Project Overview

The goal of this project is to analyze movie metadata, ratings, and revenue-related statistics to answer key business and analytical questions. The analysis explores:
- Top-rated movies and genres
- Actor and country-level performance
- Rating distributions and volatility
- Financial trends and audience engagement
- Data visualizations and dashboards for decision-making

---

## 🧩 Dataset

- **Source**: IMDb dataset (shared as Excel file with 6 sheets)
- **Tables Used**:
  - `movie`: core movie attributes (title, duration, year, income, etc.)
  - `ratings`: average, median, and total votes per movie
  - `genre`: multiple genres per movie
  - `names`: people involved (actors/directors)
  - `role_mapping`: connects people to movies
- **Size**: 9000+ movies, spanning multiple decades, countries, and languages

---

## 🛠️ Tools & Technologies

| Tool       | Purpose                        |
|------------|--------------------------------|
| **MySQL**  | Data extraction & SQL querying |
| **Python** | Data cleaning, merging, EDA    |
| **Pandas** | Data manipulation              |
| **Seaborn / Matplotlib** | Visualizations    |
| **Power BI** | Dashboarding & KPI visuals   |

---

## 🔍 Key Questions Answered

### 🔹 SQL-Based Analysis
- What are the most popular genres by ratings and votes?
- Which actors appear in the most movies and highest-rated ones?
- What is the correlation between ratings and votes?
- What countries have produced the most movies?
- How many genres are associated with each movie on average?
- Highest and lowest rated movies, rating trends over time

### 🔹 Python-Based Analysis
- Are highly voted movies better rated? (correlation plots)
- Distribution plots for average ratings, durations, and gross income
- Box, violin, strip, density plots across genres
- Pivot tables summarizing gross income per genre
- “Blockbuster disappointments” (high gross but low rating)
- “Rating volatility” (difference between avg and median rating)

### 🔹 Power BI Dashboard
- KPI cards (Total Movies, Avg Rating, Total Gross)
- Time-series charts for ratings and votes
- Actor- and genre-based slicers
- Top production companies and countries by gross income
- Drill-throughs for specific movies or actors

---

## 📈 Sample Visuals

> <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1d906dfa-815a-4da8-a636-bc9d08b65a1f" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ea0bbe4a-2125-41b2-9c43-f71dd1f4766c" />
<img width="1717" height="803" alt="image" src="https://github.com/user-attachments/assets/8ea3c778-75de-4ce4-9151-82185595c137" />
<img width="1713" height="796" alt="image" src="https://github.com/user-attachments/assets/b810a399-b0fa-46ec-bc28-3a610042ec7d" />
<img width="1650" height="489" alt="image" src="https://github.com/user-attachments/assets/e589b530-d83a-4d14-b332-98e9de80ec1e" />
<img width="1650" height="538" alt="image" src="https://github.com/user-attachments/assets/f80673c6-f1e0-4522-8bc9-94af8db2066a" />





---

## 📄 Project Structure

├── project.sql # All SQL queries used
├── project.ipynb # Python analysis (Pandas + Visualizations)
├── IMDb_movies_Data.xlsx # Dataset (6 sheets)
├── project.pbix # Power BI file
└── Project.ppt # Final PPT summary


---

## ✅ Conclusion

This project showcases a full-stack data analysis pipeline—starting from structured querying with SQL, extending to in-depth exploratory data analysis in Python, and finishing with dynamic reporting in Power BI. The insights generated can help stakeholders in media, marketing, and production make informed decisions based on audience behavior, genre performance, and financial success.

---

## 📧 Contact

**Aditya Garg**  
Email: adityagarg6969@gmail.com
