# 🎬 Data-Driven Strategy for Launching a Movie Studio

## 📝 Overview
This project aims to support the launch of a new movie studio by identifying what types of films perform best at the box office. By analyzing historical movie data, we uncover trends in genres, budgets, ratings, and other attributes that influence commercial success. The ultimate goal is to provide strategic, data-backed recommendations to guide content creation and production investments.

---

## 💼 Business Understanding

### 👥 Stakeholder
The primary stakeholder is the executive team of the company's new movie studio. They need insights into the film industry to make confident decisions on what type of movies to produce.

### ❓ Key Business Questions
- What genres perform best at the box office?
- Is there an ideal budget range that maximizes profitability?
- How do release timing and other attributes like runtime and ratings impact success?
- What are common characteristics of top-performing movies?

---

## 📊 Data Understanding and Analysis

### 📁 Source of Data
- **im.db.zip**: A zipped SQLite database containing movie metadata and ratings.
  - `movie_basics`: Contains core movie details such as title, genre, runtime, etc.
  - `movie_ratings`: Contains user and critic rating data.
- **bom.movie_gross.csv.gz**: A compressed CSV file with box office gross data for various films.

### 📄 Description of Data
The dataset includes:
- Movie titles, release years, and genres  
- Runtime and MPAA ratings  
- Viewer ratings and number of votes  
- Domestic and international box office gross  

These data points are key to understanding what makes a movie successful both critically and financially.

---

## 📈 Data Visualizations

_(Visuals to be added later — placeholder descriptions below)_

### 🎨 Visualization 1: Genre vs Average Revenue
A bar chart showing average box office revenue by genre to determine top-performing categories.

### 🧩 Visualization 2: Budget vs Revenue Scatter Plot
A scatter plot to explore the relationship between production budget and gross earnings.

### 📅 Visualization 3: Revenue by Release Month
A line or bar chart showing how revenue trends vary across different release months or seasons.

---

## ✅ Conclusion

### 🔍 Summary of Findings
- **Action Genre Leads in Revenue**: Action films consistently generate the highest average box office revenue.
- **Mid-Range Budgets Perform Best**: Films with moderate budgets tend to yield higher returns compared to low- or high-budget films.
- **Summer Releases Dominate**: Movies released in June–July see a noticeable spike in revenue, indicating strong seasonal influence.

These insights form a strategic foundation for the company’s new studio to focus on genres and production strategies with high commercial potential.

---

## 📂 Folder Structure

```bash
project-root/
│
├── data/
│   ├── im.db.zip
│   └── bom.movie_gross.csv.gz
│
├── notebooks/
│   └── movie_analysis.ipynb
│
├── visualizations/
│   └── genre_revenue_chart.png
│   └── budget_vs_revenue_plot.png
│   └── monthly_trends.png
│
├── reports/
│   └── presentation.pdf
│   └── final_report.docx
│
└── README.md
