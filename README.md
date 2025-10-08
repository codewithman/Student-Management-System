# 🎓 Student Management System (SQL Project)

## 🧠 Project Overview

The **Student Management System** is a SQL-based database project designed to efficiently manage student-related data for an educational institution.  
It handles **student records, classes, attendance tracking, and grades**, providing a foundation for student analytics and academic management.  

This project demonstrates strong understanding of **database design, normalization, relationships, SQL joins, and analytical queries**.

---

## 🏗️ Database Schema Overview

The project includes the following relational tables:

| Table Name     | Description |
|----------------|--------------|
| **Students**   | Stores basic student information such as name, gender, contact details, and address. |
| **Classes**    | Contains information about class levels and sections. |
| **Attendance** | Tracks student attendance by date, including Present, Absent, or Late status. |
| **Grades**     | Stores subjects and grades for each student. |

---

## 📦 Database Setup

### 1️⃣ Create and Use Database
```sql
DROP DATABASE IF EXISTS studentmanagement;
CREATE DATABASE studentmanagement;
USE studentmanagement;
