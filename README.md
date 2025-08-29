# Movie_Review-PySpark_Project

# Business Scenario:
We are a data analyst working for a movie streaming platform. Our task is to analyze user ratings and movie metadata to generate insights.

# Technologies: 
1.PySpark
2.Notebook
3.Power BI

# Input Files:
1. movies.csv · Contains movie_id, title, genre, country, release_year
2. users.csv · Contains user_id, country, age
3. ratings.csv · Contains user_id, movie_id, rating (1-5), rating_date

# Our Tasks:
1. Calculate average rating per movie and identify top 5 movies in each genre.
2. Calculate average rating per country (based on user country).
3. Identify rating anomalies where rating > 5 or rating < 1 (simulate a few anomalies).
4. Segment users into High (avg rating > 4), Medium (avg rating 2-4), Low (avg rating < 2).
5. Generate a summary report with:
   - Total number of ratings
   - Number of unique users and movies
   - Average rating overall
   - Most active user (by number of ratings)
