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


### 🎨 What are the most common genres produced over time

- <img src="https://github.com/user-attachments/assets/41710985-88f3-4ed7-8a0d-961719c81f51" height="250" />

### 🧩 Top 10 Movies by Domestic Gross Revenue

- <img src="https://github.com/user-attachments/assets/75202e5f-41fc-417c-976f-d09ef7b4a5e2" height="250" />

### 📅 Visualization 3: Revenue by Release Month

- <img src=" https://github.com/user-attachments/assets/e8b26a05-4d4b-4d13-b6da-47645e6b593e" height="250" />


---

---
### Business Objective 1 Finding

- **Thriller** was the most produced genre, peaking in 2018 before dropping sharply in 2019.
- A slight rise in Western movies was seen in 2012 and 2018 but wasn't maintained.


 ### 🎯 **Recommendations**

 -  **Niche Opportunities**: Explore ways to grow interest in less popular genres like Sport and Western through innovation or targeted marketing.
    
- **Market Monitoring**: Track shifting audience interests, especially after the 2019 drop, to adjust production strategies.
  
---

---

### Business Objective 2  Finding

- **Thriller** was the most produced genre, peaking in 2018 before dropping sharply in 2019.
- A slight rise in Western movies was seen in 2012 and 2018 but wasn't maintained.


 ### 🎯 **Recommendations**

 -  **Niche Opportunities**: Explore ways to grow interest in less popular genres like Sport and Western through innovation or targeted marketing.
    
- **Market Monitoring**: Track shifting audience interests, especially after the 2019 drop, to adjust production strategies.
  
---

---

### Business Objective 3 Finding

- **Thriller** was the most produced genre, peaking in 2018 before dropping sharply in 2019.
- A slight rise in Western movies was seen in 2012 and 2018 but wasn't maintained.


 ### 🎯 **Recommendations**

 -  **Niche Opportunities**: Explore ways to grow interest in less popular genres like Sport and Western through innovation or targeted marketing.
    
- **Market Monitoring**: Track shifting audience interests, especially after the 2019 drop, to adjust production strategies.
  
---

## ✅ Conclusion

### 🔍 Summary of Findings
- **Action Genre Leads in Revenue**: Action films consistently generate the highest average box office revenue.
- **Mid-Range Budgets Perform Best**: Films with moderate budgets tend to yield higher returns compared to low- or high-budget films.
- **Summer Releases Dominate**: Movies released in June–July see a noticeable spike in revenue, indicating strong seasonal influence.

These insights form a strategic foundation for the company’s new studio to focus on genres and production strategies with high commercial potential.

---

## 📂 Folder Structure


Group4-Phase2-Project/
│
├── zippedData/
│   ├── im.db.zip
│   └── bom.movie_gross.csv.gz
│
```├── /
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
