# MSSQL-DATABASE
IT IA AN ONLINE COURSES LEARNING PLATFORM DATABASE
## 📌 Project Overview
**LEARNHUB** is a database-driven **Online Learning Platform Management System** designed to manage students, courses, enrollments, quizzes, payments, and performance analytics.  
This project demonstrates **end-to-end database design and advanced SQL concepts**, simulating how real-world e-learning platforms operate.

The system efficiently tracks student progress, course performance, faculty ratings, quiz attempts, and payment balances using relational integrity and automation through triggers, procedures, and functions.

---

## 🎯 Project Objectives
- Design a **realistic relational database** for an online learning platform
- Maintain **data integrity using constraints and relationships**
- Automate actions using **triggers**
- Perform business analysis using **views, functions, and stored procedures**
- Practice **real-world SQL queries** for analytics and reporting

---

## 🧩 Key Features
- Student registration and profile management
- Course catalog with duration and pricing
- Faculty assignment with ratings
- Student enrollments with progress tracking
- Automatic enrollment activity logging using triggers
- Quiz management and performance tracking
- Course reviews and feedback system
- Payment tracking with balance calculation
- Analytical reports on course and student performance

---

## 🗂️ Database Schema (Core Tables)
- `STUDENT`
- `COURSE_DETAILS`
- `FACULTIES`
- `ENROLLMENT`
- `QUIZ`
- `QUIZATTEMPT`
- `COURSE_REVIEW`
- `PAYMENT_DETAILS`
- `ENROLLMENT_LOG`

Each table is implemented with:
- PRIMARY KEYS
- FOREIGN KEYS
- UNIQUE & CHECK constraints
- Default values

---

## ⚙️ Automation & Advanced SQL
- **Triggers**
  - Logs enrollment activity (INSERT, UPDATE, DELETE)
  - Automatically updates student active status based on completion
- **Views**
  - Consolidated student and course information
- **Functions**
  - Calculates remaining payment balance per student
- **Stored Procedures**
  - Generates overall course performance analytics

---

## 📊 Sample Analytics & Queries
- Students with low performance
- Highest quiz scores
- Course-wise enrollment and completion rate
- Average quiz scores and faculty ratings
- Active vs completed enrollments
- Outstanding payment balances

---

## 🛠️ Tech Stack
- **Database**: SQL Server  
- **Language**: SQL (DDL, DML, DCL concepts)  
- **Tools**: SQL Server Management Studio, Git, GitHub  

---

## 🚀 How to Run the Project
1. Install **SQL Server** and **SSMS**
2. Clone the repository:
   ```bash
   git clone https://github.com/your-username/learnhub-database-project.git
