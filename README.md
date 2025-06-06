# Exam-System

📚 Exam System Mini Project (Java + SQL)

🔍 Project Overview

The Exam System Mini Project is a simple yet functional desktop-based application designed to conduct and manage online examinations for students. Developed using **Java** for the frontend (logic & interface) and MySQL (or any RDBMS using SQL) for backend data storage, this project mimics a real-world test-taking environment.

The system allows **admin users** to create and manage exams, questions, and students, while **students** can log in, take tests, and receive instant results.

🛠️ Technologies Used

Java (Core Java / Swing / JDBC) – for building the user interface and handling logic
MySQL / SQL – for database management (storing users, questions, and results)
JDBC (Java Database Connectivity) – for connecting Java with the database

👤 User Roles

* *Admin:*

  * Add/edit/delete questions
  * View student scores
  * Manage exam schedule (optional)

* *Student:*

  * Register and login
  * Take assigned exams
  * View score after submission

📁 Main Modules

1. Login/Registration System
2. Question Management (CRUD operations for Admin)
3. Exam Interface

   * Timed or untimed exams
   * Single-choice/multiple-choice questions
4. **Result Calculation**

   * Score display on submission
   * Option to store results in database
5. **Database Tables** (sample)

   * `users` – stores student/admin login info
   * `questions` – holds exam questions
   * `results` – keeps student scores and timestamps
