# imdb-movie-rating-poject
SQL-based IMDB movie data analysis project using MySQL. Includes data exploration, queries, insights, joins, aggregations, and business-oriented analysis on movies, ratings, genres, and actors.

# IMDB Movie Data Analysis using SQL

## Project Overview
This project focuses on analyzing IMDB movie data using SQL queries in MySQL.  
The dataset contains information about movies, genres, ratings, actors, directors, and production companies.

The objective of this project is to perform:
- Data exploration
- Data cleaning checks
- Trend analysis
- Business insights extraction
- Aggregations and joins
- Advanced SQL querying

This project demonstrates practical SQL skills commonly used in:
- Data Analytics
- Data Science
- Business Intelligence
- Database Management

---

## Tools & Technologies
- MySQL
- SQL
- IMDB Dataset

---

## Database Tables Used
The project uses the following tables:

- `movie`
- `genre`
- `ratings`
- `names`
- `director_mapping`
- `role_mapping`

---

## Key Analysis Performed

### 1. Data Exploration
- Total rows in each table
- Checking null values
- Understanding table structure

### 2. Movie Trend Analysis
- Movies released year-wise
- Month-wise movie release trends
- Country-wise movie production

### 3. Ratings Analysis
- Highest rated movies
- Average movie ratings
- Ratings distribution

### 4. Genre Analysis
- Most popular genres
- Genre-wise movie count
- Genre performance comparison

### 5. Actor & Director Analysis
- Top directors based on ratings
- Actor performance analysis
- Role mapping insights

### 6. Business Insights
- Production company analysis
- Revenue-related analysis
- Industry trends

---

## SQL Concepts Used
This project covers important SQL concepts including:

- SELECT statements
- WHERE clause
- GROUP BY
- ORDER BY
- Aggregate Functions
- CASE Statements
- JOIN operations
- Subqueries
- Aliases
- Filtering
- Sorting
- NULL handling

---

## Sample Queries

### Total Movies by Year
```sql
SELECT year, COUNT(id) AS number_of_movies
FROM movie
GROUP BY year;
