# Databases-and-SQL
# 🗃️ Data Technician Workbook – Week 3

href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mysql-colored.svg" width="36" height="36" alt="MySQL" 

## 📚 Overview

This workbook provides foundational and applied knowledge in:

- Database concepts (keys, relationships, relational vs. non-relational models)
- SQL operations (JOINs, INSERTs, SELECTs, filtering, aggregating)
- Database design for a real-world retail use case
- Querying and analysis with the `world_db` database

---

## 📆 Tasks by Day

### 🔹 Day 1: Database Concepts
- Defined **primary**, **secondary**, and **foreign keys**
- Explored real-world relationship types:
  - One-to-one (e.g., passport and person)
  - One-to-many (e.g., department to employees)
  - Many-to-many (e.g., students and classes)

---

### 🔹 Day 1: Relational vs. Non-Relational
- Compared data models, structure, and scalability
- Non-relational benefits explained for:
  - Unstructured data (e.g., images, articles)
  - Real-time applications (e.g., social media)

---

### 🔹 Day 3: SQL JOINs
Explained and demonstrated 6 JOIN types:
- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN`
- `FULL JOIN`
- `CROSS JOIN`
- `SELF JOIN`

Includes examples of when to use each JOIN type in real-world data scenarios.

---

### 🔹 Day 4: Database Design (Retail Shop Project)
Designed a SQL-based database for a convenience store, including:
- Schema for tables: `Products`, `Customers`, `Sales`, `SaleDetails`, `Suppliers`
- Defined relationships with `FOREIGN KEY`s
- SQL examples: `CREATE TABLE`, `INSERT INTO`, referential integrity

Covered:
- Inventory management
- Loyalty points tracking
- Secure data access and backup practices

---

## 🧪 SQL Practice (World Database)
Ran and documented SQL queries using `world_db` to answer real-world questions, such as:
- ✅ Most/least populated cities
- 🌍 Country with highest life expectancy
- 📊 Cities with GDP per capita above average
- 🌎 Capital cities and cities by region
- 🧠 Frequency of city names
- 🏙️ Cities starting with 'New' or 'Be'
- 🔢 Cities with populations between given thresholds

Queries included:
```sql
SELECT COUNT(*) AS TotalCitiesInUSA FROM City WHERE CountryCode = 'USA';
SELECT Name, LifeExpectancy FROM Country ORDER BY LifeExpectancy DESC LIMIT 1;
SELECT Name AS City FROM City WHERE Name LIKE 'New%';
📎 Files Included
📄 Workbook PDF: Data_Technician_Workbook_Week_3_Husam_Asif.pdf

💻 Screenshots and SQL outputs embedded in the PDF

🧰 Tools & Skills Practiced
SQL: Query writing, database creation, joins, filtering, sorting

Database Design: Normalization, keys, entity relationships

Critical Thinking: Translating business needs into structured data systems

📬 Submission Info
Workbook completed and submitted as part of the Just IT Data Technician course.

Feel free to explore the queries and get in touch if you’d like to discuss database design or optimization strategies!
