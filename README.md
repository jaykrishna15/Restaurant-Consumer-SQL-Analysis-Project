# 🍽️ Restaurant & Consumer SQL Analysis Project

This project focuses on analyzing a **Restaurant–Consumer relational database** using **SQL**, covering everything from basic filtering to advanced analytical queries.  
It demonstrates practical usage of SQL concepts commonly required in **data analytics, internships, and entry-level roles**.

---

## 📌 Project Objectives

- Understand relationships between consumers, restaurants, cuisines, and ratings
- Apply SQL filtering using `WHERE`
- Perform multi-table analysis using `JOINs`
- Use subqueries, CTEs, window functions, views, and stored procedures
- Derive business insights from real-world restaurant data

---

## 🗂️ Database Structure

The database consists of the following tables:

- `consumers` – demographic and lifestyle information
- `restaurants` – restaurant details and facilities
- `ratings` – consumer ratings for restaurants
- `consumer_preferences` – preferred cuisines
- `restaurant_cuisines` – cuisines served by restaurants

Foreign key constraints are used with **CASCADE** to maintain referential integrity.

---

## 🔹 SQL Concepts Covered

### 1️⃣ Basic Filtering (WHERE Clause)
- Consumers from specific cities (e.g., Cuernavaca)
- Students, smokers, social drinkers
- Restaurants by price, franchise status, alcohol service
- Rating-based filtering

### 2️⃣ JOINs & Subqueries
- Consumers who rated restaurants in specific cities
- Cuisine-specific restaurant ratings
- EXISTS / NOT EXISTS queries
- Aggregate filtering using `HAVING`

### 3️⃣ Aggregations & Grouping
- Average ratings
- Rating counts per consumer
- Restaurants below average food rating

### 4️⃣ Advanced SQL
- **CTEs (WITH clause)**
- **Window Functions**: `RANK`, `DENSE_RANK`, `ROW_NUMBER`, `AVG() OVER`
- **Views** for reusable logic
- **Stored Procedures** for parameterized analysis

---

## 📊 Key Analytical Use Cases

- Top consumers based on average ratings
- Highly rated Mexican restaurants
- Consumers who prefer Mexican cuisine but never rated top Mexican restaurants
- Ranking restaurants within cuisines
- Comparing individual ratings against restaurant averages

---

## 🛠️ Libraries / Tools Used

- 🐬 **MySQL**
- 💻 SQL (DDL, DML, Advanced Queries)

---

## 🎯 Learning Outcome

By completing this project, I gained hands-on experience in:
- Writing optimized SQL queries
- Solving real-world analytical problems using SQL
- Structuring complex queries using CTEs and window functions
- Building reusable database components (Views & Procedures)

---

## 📎 How to Use

1. Run table creation scripts  
2. Apply foreign key constraints  
3. Execute queries section-by-section for learning and analysis  

---

## 🚀 Author

**Jaya Krishna Golla**  
SQL | Data Analytics | Learning Journey
