# 🎓 University Management System PERN Stack

A full-stack **University Management System** built using the **PERN stack (PostgreSQL, Express, React, Node.js)** to manage academic and administrative operations efficiently.

This system is designed with real-world university workflows in mind, focusing on scalability, security, and clean architecture.

---

## 📌 Table of Contents

- Overview  
- Features  
- Tech Stack  
- System Architecture  
- User Roles  
- Installation  
- Environment Variables  
- API Structure  
- Database Design  
- Security  
- Future Scope  
- Contributing  
- License  

---

## 📖 Overview

The **University Management System (UMS)** is a centralized platform that helps universities manage:

- Students  
- Faculty  
- Courses  
- Attendance  
- Results  
- Administrative operations  

The application replaces manual processes with a digital, role-based, and secure solution.

---

## ✨ Features

### 🎓 Student
- Secure authentication  
- View profile and academic details  
- Course enrollment  
- Attendance and results tracking  

### 👨‍🏫 Faculty
- Manage assigned courses  
- Mark and update attendance  
- Upload grades  
- View enrolled students  

### 🏢 Admin
- Manage students, faculty, and departments  
- Create and assign courses  
- Control semesters and academic years  
- System-level access and analytics  

### 🔐 Authentication
- JWT-based authentication  
- Role-based authorization  
- Encrypted passwords  

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- React Router  
- Axios  
- Tailwind CSS / CSS Modules  

### Backend
- Node.js  
- Express.js  
- RESTful APIs  

### Database
- PostgreSQL  

### Tools & Libraries
- JWT  
- bcrypt  
- dotenv  
- Git & GitHub  

---

## 🧱 System Architecture

```text
Client (React)
    |
    | REST API
    |
Server (Node + Express)
    |
    |
Database (PostgreSQL)
