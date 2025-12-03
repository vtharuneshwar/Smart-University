# 🎓 Smart University — SQL Database Project

![SQL](https://img.shields.io/badge/Database-SQL-blue)
![MySQL](https://img.shields.io/badge/MySQL-Compatible-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

A complete SQL-based Smart University Database System designed to efficiently manage and analyze academic information. This project includes a relational database schema, sample data, queries, ER diagram overview, and documentation.

---

## 📁 **Project Contents**

- **smart_university.sql**  
  Full SQL schema, relationships, sample data, and example queries.  
- **SQL_SMART_UNIVERSITY.pptx**  
  Presentation with project explanation and ER Diagram.  
- **docs/schema_overview.md**  
  Documentation of all tables and relationships.  
- **docs/ER_diagram_ascii.md**  
  ASCII representation of database ER Diagram.  
- **LICENSE** (MIT)  
- **.gitignore**, **CONTRIBUTING.md**, **CODE_OF_CONDUCT.md**

---

## 🧠 **Project Features**

- Student information management  
- Faculty and department tracking  
- Course catalog with prerequisites  
- Enrollment system  
- Exam management (Midterm, Final, Quiz)  
- Result tracking  
- Attendance tracking  
- Fee management (due, paid, deadlines)  
- Analytics via SQL queries:
  - Failed students  
  - Fee defaulters  
  - Department-wise student count  
  - Enrolled students per course  
  - Student exam results and performance reports

---

## 🗄️ **Database Technology**

- **MySQL-compatible SQL**
- Uses:
  - Primary Keys  
  - Foreign Keys  
  - Composite Keys  
  - Constraints (CHECK, UNIQUE, ENUMs)  
  - Joins (INNER, LEFT, RIGHT)  
  - Subqueries  
  - GROUP BY / HAVING  

This project models real-world university data using clean relational design.

---

## 🚀 **How to Run**

### 1️⃣ Create Database
```sql
CREATE DATABASE smart_university;
USE smart_university;
