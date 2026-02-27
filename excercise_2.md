# SQL Bolt - Exercise 2 – Tasks

**Date:** [Insert Date – e.g. 06/02/2026]  
**AIM:** To practice SELECT queries with filtering (WHERE), range conditions (BETWEEN, NOT BETWEEN), and limiting results (LIMIT) on the movies table from SQL Bolt.

**Database:** movies (SQL Bolt online platform)  
**Table:** movies  
**Columns:** id, title, director, year, length_minutes

**Note:**  
- All queries are executed in the SQL Bolt online editor  
- Screenshots show full query + result table from SQL Bolt  
- Results are based on the SQL Bolt movies dataset (Toy Story, Finding Nemo, etc.)

## 1. Find the movie with a row id of 6

```sql
SELECT * FROM movies 
WHERE id = 6;
```
## 2. Find the movies released in the years between 2000 and 2010
```sql
SELECT * FROM movies 
WHERE year BETWEEN 2000 AND 2010;
```
## 3. Find the movies not released in the years between 2000 and 2010

```SQL
SELECT * FROM movies 
WHERE year NOT BETWEEN 2000 AND 2010;
```
## 4. Find the first 5 Pixar movies and their release year

```SQL
SELECT title, year FROM movies 
ORDER BY year ASC 
LIMIT 5;
