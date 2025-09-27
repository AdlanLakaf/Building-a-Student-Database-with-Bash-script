Student Database - freeCodeCamp Project
A bash script project that creates and populates a PostgreSQL student database with data from CSV files.
Description
This project builds a relational database for student information using PostgreSQL and bash scripting. It reads data from CSV files and populates tables for majors, courses, students, and their relationships.
Database Structure

majors - Academic majors
courses - Available courses
students - Student information
majors_courses - Relationship between majors and courses

Files

insert_data.sh - Main bash script to populate database
courses.csv - Course and major data
students.csv - Student enrollment data
students.sql - Database backup/dump file

Requirements

PostgreSQL
Bash shell
CSV data files

Usage

Set up PostgreSQL database named 'students'
Make script executable:

bash   chmod +x insert_data.sh

Run the script:

bash   ./insert_data.sh
Features

Automatically creates database relationships
Handles duplicate data prevention
Processes CSV files with proper parsing
Provides feedback during data insertion

freeCodeCamp
This project is part of the freeCodeCamp Relational Database curriculum, focusing on bash scripting and PostgreSQL database management.

