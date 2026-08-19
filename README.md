# Enterprise HRMS SaaS Platform

## Professional Project Showcase

Enterprise HRMS is a full-stack Human Resource Management System designed to centralize and manage organizational workforce operations through a secure, database-driven SaaS platform.

This repository is a **public project showcase only**.

> The application source code is maintained in a separate private repository and is not included here.

---

## 🚀 Live Application

### HRMS Application

[Open Enterprise HRMS](https://hrms-ufp1.onrender.com)

The application is deployed as a cloud-hosted full-stack application.

---

## 🎥 Complete Application Demonstration
[hrms.webm](https://github.com/user-attachments/assets/4b9d5ab0-4850-4600-9be1-c7a2d86f4123)


The demonstration covers the complete HRMS workflow and major application modules.

---

# 📌 Project Overview

The Enterprise HRMS platform provides an integrated solution for managing employee lifecycle, workforce operations, recruitment, payroll, training, organizational assets, documentation and internal communication.

The system follows a modern full-stack architecture with a React frontend, Node.js/Express backend and MySQL database hosted on Aiven.

---

# ✨ Major Features

## 🔐 Authentication & Security

- User login
- Logout
- Role-based access control
- Admin privileges
- Employee privileges
- HR privileges
- Session management
- JWT-based authentication
- Secure password handling
- Protected application routes

---

## 👥 Employee Management

- Employee Directory
- Add employees
- Update employee information
- Delete employees
- Employee profiles
- Department assignment
- Designation assignment
- Employee status management

---

## 🏢 Organization Management

- Departments
- Designations
- Organizational structure
- Salary bands
- Employee-to-department mapping
- Employee-to-designation mapping

---

## 🕒 Attendance & Shift Management

- Attendance tracking
- Clock-in
- Clock-out
- Shift management
- Attendance records
- Workforce tracking

---

## 🏖️ Leave Management

- Leave applications
- Leave balances
- Leave approval workflow
- Leave rejection
- Pending approvals
- Leave history
- Leave types

---

## 💰 Payroll

- Payroll processing
- Employee salary information
- Payslip management
- Payroll records
- Salary-related data management

---

## 🎯 Recruitment & ATS

- Job requisitions
- Job openings
- Candidate management
- Recruitment pipeline
- Candidate status tracking
- Hiring workflow

---

## 🎓 Training & Development

- Training courses
- Course management
- Employee training
- Training status
- Development tracking

---

## 💻 Company Assets

- Asset registration
- Asset assignment
- Asset tracking
- Asset status
- Employee asset mapping

---

## 📄 Documents & Policies

- Document repository
- Policy management
- Document upload
- Document metadata
- Policy organization

---

## 📢 Announcements & Holidays

- Company announcements
- Broadcast messages
- Holiday calendar
- Holiday management
- Employee notifications

---

## 🔔 Notifications

- Application notifications
- Leave notifications
- HR notifications
- System notifications
- User-specific notifications

---

## 👤 User Management

- User creation
- User roles
- Privilege management
- User activation/deactivation
- Authentication management

---

## 📊 Reports & Analytics

- HR reports
- Employee statistics
- Workforce analytics
- Attendance analytics
- Recruitment information
- Payroll information

---

# 🛠️ Technology Stack

| Layer | Technology |
|---|---|
| Frontend | React |
| Language | TypeScript |
| Backend | Node.js |
| API | Express.js |
| Database | MySQL |
| Database Hosting | Aiven |
| Application Hosting | Render |
| Source Control | GitHub |
| Authentication | JWT / Session Management |
| AI Integration | Google Gemini |
| Build Tool | Vite |
| Database Driver | MySQL2 |

---

# ☁️ Cloud Architecture

```text
                         USERS
                           |
                           v
                  +----------------+
                  |    Internet    |
                  +-------+--------+
                          |
                          v
              +-----------------------+
              |       RENDER          |
              |                       |
              | React Frontend        |
              | Node.js Backend       |
              | Express APIs          |
              +----------+------------+
                         |
                    TLS / SSL
                         |
                         v
              +-----------------------+
              |       AIVEN           |
              |                       |
              | MySQL 8.4             |
              | hrms-db                |
              +-----------------------+
