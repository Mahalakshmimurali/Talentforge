# 💼 TalentForge – Recruitment & Interview Management System

**TalentForge** is a web-based application designed to streamline and digitize the hiring process. It offers powerful role-based functionalities for both **candidates** and **administrators**, covering everything from job posting to final evaluation.

Built using **Spring Boot**, **Thymeleaf**, **Bootstrap**, and **MySQL**, TalentForge combines simplicity with enterprise-grade features like email notifications, dashboards, analytics, and secure access control.

---

## 🚀 Key Features

### 👨‍💻 Candidate Portal
- Browse and filter job vacancies based on departments and criteria.
- Submit applications with resume uploads.
- Receive email updates on application status.

### 🧑‍💼 Admin Portal
- Create and manage job postings.
- View applicant lists and profiles.
- Schedule interviews and manage evaluation rounds.
- Track application pipeline visually with dashboards.

### 🛡️ Role-Based Access (6 Administrative Roles)
| Role             | Access Privileges |
|------------------|-------------------|
| **Default Admin** | Full system access, role assignments |
| **Admin**         | Manage jobs, users, and evaluations |
| **Senior HR**     | Schedule interviews, review candidates |
| **Junior HR**     | Assist in screening and communication |
| **Department Head** | Approve hiring decisions |
| **Interviewer**   | Provide candidate evaluations |

---

## 🧰 Tech Stack

- **Backend**: Spring Boot (Java), Spring Security
- **Frontend**: Thymeleaf, HTML5, CSS3, JS, Bootstrap
- **Database**: MySQL
- **Build Tool**: Maven
- **IDE**: Spring Tool Suite (STS) or IntelliJ

---

## 📂 Project Structure
TalentForge/
├── src/
│ ├── main/
│ │ ├── java/com/talentforge/ # Controllers, Services, Repositories
│ │ └── resources/
│ │ ├── templates/ # Thymeleaf HTML templates
│ │ └── static/ # CSS, JS, images
├── pom.xml # Project dependencies
└── README.md

**MYSQL Database**

spring.datasource.url=jdbc:mysql://localhost:3306/recruitment
spring.datasource.username=root
spring.datasource.password=yourpassword

