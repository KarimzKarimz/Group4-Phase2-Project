# Group4-Phase2-Project
## Data Insights for building a new movie studio
### Overview
- The company is determine dto venture into movie production industry based majorly on the succes of otehr big studios. To guide the company we'll do Explanatory Data Analysis, genre trends using datasets from Box Office Mojo, IMDB, and other sources. 
- The goal is to determine what type of movies best perform commercially and critically translate the insights into actionable recommendations.
## Business Understanding
- Despite the big compoanies still greatly investing in the movie industry, our company aims to launch a new movie studion and grab part of the growing market even though the company lacks experience to make informed decision on what movies the market needs produced.
- Among the key business questions are; 
- (i) Which genres consistently generate the highest box office revenue? 
- (ii) What movie ratings (G, PG, PG-13, R) are associated with the most financial success?
- (iii) How does movie duration (runtime) correlate with box office performance?
- (iv) How does the release month or season impact a movie’s earnings?
## Data Understanding and Analysis
### Sources of Data
- **im.db.zip**: A zipped SQLite database containing movie metadata and ratings.
- `movie_basics`: Contains core movie details such as title, genre, runtime, etc.
- `movie_ratings`: Contains user and critic rating data.
- **bom.movie_gross.csv.gz**: A compressed CSV file with box office gross data for various films.

### Description of Data
The dataset includes:
- Movie titles, release years, and genres  
- Runtime and MPAA ratings  
- Viewer ratings and number of votes  
- Domestic and international box office gross  

These data points are key to understanding what makes a movie successful both critically and financially.
## Data Visualization
 - The goal is to use clear and isightful visuals to explore trends and support business recommendations
 ### 🎨 Visualization 1: Genre vs Average Revenue
A bar chart showing average box office revenue by genre to determine top-performing categories.

### 🧩 Visualization 2: Budget vs Revenue Scatter Plot
A scatter plot to explore the relationship between production budget and gross earnings.

### 📅 Visualization 3: Revenue by Release Month
A line or bar chart showing how revenue trends vary across different release months or seasons.

## Conclusion
### Summary of findings
- Genre Matters: Action, Adventure, and Animation consistently generate the highest box office revenues. Investing in these genres increases the probability of financial success.

- Timing is Critical: Movies released during the summer (June–July) and the holiday season (November–December) tend to perform better, suggesting that strategic release timing can boost earnings.

- Quality Pays Off: Higher IMDB ratings are moderately correlated with higher box office grosses, meaning quality storytelling and production values still matter.

- Runtime Sweet Spot: Most successful movies have a runtime between 100–130 minutes — long enough to develop a story but not so long that it reduces audience interest.
