# IMDb Movies SQL Analysis Project

## 📌 Project Overview

This project focuses on analyzing IMDb movie data using **SQL** to extract meaningful insights from structured datasets. The goal is to demonstrate practical SQL skills such as working with multiple tables, joins, filtering, aggregation, and analytical queries on a real-world dataset.

The project simulates common data analysis tasks that are typically required in **Data Analyst** roles.

---

## 📂 Dataset Description

The project uses two relational tables:

### 1️⃣ Movies Table

Contains detailed information about movies.

* `movie_id`
* `original_title`
* `budget`
* `revenue`
* `popularity`
* `release_date`
* `director_id`

### 2️⃣ Directors Table

Contains information about movie directors.

* `director_id`
* `director_name`

These tables are connected using the **director_id** column.

---

## 🔗 Database Relationship

* One director can direct multiple movies.
* Relationship type: **One-to-Many**
* Primary Key: `director_id` (Directors table)
* Foreign Key: `director_id` (Movies table)

---

## 🛠 Tools & Technologies Used

* SQL (MySQL / PostgreSQL compatible)
* GitHub (Version Control)
* DBMS for query execution

---

## 📊 Key SQL Concepts Applied

* `SELECT` queries
* `WHERE` filtering
* `ORDER BY` and `LIMIT`
* Aggregate functions (`SUM`, `AVG`, `COUNT`, `MAX`, `MIN`)
* `GROUP BY`
* `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`
* Subqueries
* Aliases

---

## ❓ Business Questions Solved

Some of the analytical questions answered in this project include:

* Retrieve complete movie details along with director names
* Find movies with the highest budget and revenue
* Analyze popularity trends across movies
* Identify directors with the most movies
* Compare budget vs revenue performance
* Filter movies based on release year and popularity

---

## 📈 Insights Generated

* High-budget movies do not always guarantee high revenue
* Certain directors consistently produce popular movies
* Popularity can vary significantly even within the same director’s movies
* SQL joins are essential for combining normalized datasets

---

## 🎯 Learning Outcomes

* Hands-on experience with real-world SQL datasets
* Strong understanding of joins and relational databases
* Ability to write optimized and readable SQL queries
* Improved analytical and problem-solving skills

---

## 👨‍💻 Author

**Ankit Raj Sinha**
Aspiring Data Analyst | SQL | Excel | Power BI

---

## ⭐ Acknowledgment

This project was created for learning and portfolio purposes to demonstrate SQL data analysis skills using IMDb movie data.

---

Feel free to ⭐ this repository if you find it helpful!
