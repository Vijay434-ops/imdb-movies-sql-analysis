# imdb-movies-sql-analysis
IMDB Movies &amp; Directors data analysis using MySQL to derive business insights

# IMDB Movies Data Analysis using SQL

## 📌 Project Overview
This project focuses on analyzing IMDB movie and director data using MySQL to uncover insights related to movie popularity, revenue performance, ratings, and director productivity. The analysis answers real-world business questions using structured SQL queries.

## 🛠 Tools & Technologies
- MySQL
- SQL
- Relational Database Concepts_toggle

## 📂 Dataset Overview
The dataset consists of two relational tables stored in a MySQL database:

### Tables Used
- **Movies**
  - id, uid, title, budget, revenue, popularity, vote_average, release_date, director_id
- **Directors**
  - id, name, gender, department

### Table Relationship
- `directors.id = movies.director_id`

This relationship enables combined analysis of movies and their respective directors.

## 🎯 Project Objectives
- Retrieve and explore movie and director data
- Count and filter directors based on different conditions
- Analyze movie popularity, revenue, and ratings
- Identify the most productive and bankable directors
- Answer real-world business questions using SQL

## 📊 Key SQL Analysis Performed
- Total number of movies in IMDB
- Directors name filtering and pattern matching
- Count of female directors
- Top 3 most popular movies
- Top 3 most bankable movies based on revenue
- Highest-rated movie released after January 1, 2000
- Movies directed by a specific director
- Director with the highest number of movies
- Most bankable director based on total revenue

## 🧠 Key Insights
- A small number of directors contribute to a large share of movies and revenue
- Revenue and popularity do not always correlate with higher ratings
- Only a few directors consistently deliver high-performing movies
- Female director representation is limited but impactful

## ✅ Conclusion
This project demonstrates strong SQL skills including joins, aggregations, filtering, sorting, and relational data analysis. The insights derived support data-driven decision-making and reflect real-world business analysis capability.
