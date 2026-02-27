# SQL Bolt - Exercise 1 – Tasks

**Date:** [Insert Date – e.g. 06/02/2026]  
**AIM:** To practice basic SELECT queries on the movies table using the SQL Bolt platform, retrieving specific columns and all information.

**Database:** movies (from SQL Bolt platform)  
**Table:** movies  
**Columns:** (assumed: title, director, year, and others as per SQL Bolt Exercise 1)

**Note:**  
- All queries are executed in the SQL Bolt online editor or MySQL shell  
- Screenshots show full command + output for each task  
- Results are based on the SQL Bolt movies dataset

## 1. Find the title of each film

**Query:**
```sql
SELECT title FROM movies;
```
## 2. Find the director of each film
**Query:**
```SQL
SELECT director FROM movies;
```
## 3. Find the title and director of each film
**Query:**
````SQL
ELECT title, director FROM movies;
````
## 4. Find the title and year of each film
**Query:**

```sql
SELECT title, year FROM movies;
```

## 5. Find all the information about each film
**Query:**
SQLSELECT * FROM movies;
Expected Output:
Full table with all columns and rows (title, director, year, and any other fields)
```
```sql
SELECT * FROM movies LIMIT 5;