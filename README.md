![image](https://github.com/user-attachments/assets/75f59c86-8b5d-4171-9759-7d485dc160e4)# 🎓 University Examination System

This project is a relational database model for a **University Examination System**, designed using SQL. It captures entities like departments, faculty members, courses, students, exams, and exam attempts. The system supports key functionalities such as student enrollment, exam creation, and attempt tracking.

---

## 📌 Project Objectives

- Maintain department and course structure.
- Track faculty roles such as teaching, coordination, and departmental headship.
- Manage student enrollments and attendance.
- Record exam details, including internal/external exams.
- Capture multiple student attempts and marks for each exam.

---

## 🧱 Database Schema Overview

The schema consists of the following main entities and relationships:

- **Department**: Each with a unique name and headed by a faculty member.
- **Faculty**: Employees with ID, name, and designation; can handle multiple roles.
- **Course**: Belongs to a department and coordinated by a faculty member.
- **Student**: Has a roll number, name, and belongs to a department.
- **Enrollment**: Tracks students enrolled in courses along with attendance percentage.
- **Exam**: Created by faculty, linked to a course, and has attributes like type, date, and duration.
- **ExamAttempt**: Records individual student attempts and marks for exams.

  ![Uploading image.png…]()

