# 🎓 Student Database - freeCodeCamp Project

![Bash](https://img.shields.io/badge/bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![freeCodeCamp](https://img.shields.io/badge/freecodecamp-27273D?style=for-the-badge&logo=freecodecamp&logoColor=white)

A bash script project that creates and populates a PostgreSQL student database with data from CSV files.

## 📝 Description

This project builds a relational database for student information using PostgreSQL and bash scripting. It reads data from CSV files and populates tables for majors, courses, students, and their relationships.

## 🗄️ Database Structure

| Table | Description |
|-------|-------------|
| `majors` | Academic majors |
| `courses` | Available courses |
| `students` | Student information |
| `majors_courses` | Relationship between majors and courses |

## 📁 Files

| File | Purpose |
|------|---------|
| `insert_data.sh` | Main bash script to populate database |
| `courses.csv` | Course and major data |
| `students.csv` | Student enrollment data |
| `courses_test.csv` | Test data for development |
| `students.sql` | Database backup/dump file |

## ⚙️ Requirements

- ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-12%2B-blue) 
- ![Bash](https://img.shields.io/badge/Bash-4.0%2B-green)
- CSV data files

## 🚀 Usage

<details>
<summary>💡 Quick Start Guide</summary>

1. **Set up PostgreSQL database named 'students'**
2. **Make script executable:**
```bash
   chmod +x insert_data.sh
