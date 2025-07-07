# SQL Data Analysis Project – Airports & Aircrafts ✈️

This project demonstrates advanced SQL data analysis using an aviation-related dataset that includes **airports**, **airlines**, **aircrafts**, **routes**, and **countries**. It includes aggregation, filtering, joins, views, materialized views, and indexing techniques.

---

## 📊 Features & Queries

- Count total rows, average elevation, and min/max elevation of airports.
- Group and filter airports by country with average elevation.
- Count airports by country or city and filter high-traffic cities.
- Identify aircraft types starting with “74” (e.g., Boeing 747).
- Compare wake sizes for Boeing and Airbus aircraft.
- Analyze aircrafts used in routes ending in France, Germany, Spain, and Italy.
- Create and use SQL Views and Materialized Views.
- Refresh materialized views and test with insert operations.
- Create index on columns for performance optimization.
- Use subqueries (both in `WHERE` and `FROM`) for clean analysis.
- Count distinct airlines or aircraft by country destinations.

---

## 🧰 Technologies

- **PostgreSQL**
- **SQL (Standard, with PostgreSQL-specific features)**
- pgAdmin (for query execution)

---

## 📁 File Contents

- `airport_aircraft_analysis.sql`: The full SQL script with all queries.
- `README.md`: Project overview and highlights.

---

## 📷 Sample Output (Descriptions)

- Number of airports in each country sorted by highest count.
- Average elevation of airports per country, filtered to ≥ 300m.
- Count of aircrafts flying into France.
- View of aircrafts that depart from `Lester B Pearson Intl`.
- Index created on `city` column for performance boost.

---

## 🙋 Author

**Harpreet Singh**  
Algonquin College | 041127993  
[GitHub](https://github.com/HarpreetComputerEng)

