# Dev16 Blog Platform

A robust, cloud-native blog platform featuring secure administration, scalable architecture, and modern development  techniques

---

## Overview

**Dev16 Blog** is a full-featured content management system designed for professional blogging and seamless content delivery. The platform isfocused  on   <Strong>scaling</Strong>

---

## System Architecture

- **Frontend:** Deployed on Firebase 
- **Backend:** Hosted on Render for scalable REST API services.
- **Database:** Managed MySQL instance provisioned via Aiven Cloud

**Architecture Diagram:**

```bash
[User] ⇄ [Firebase Frontend ] ⇄ [Render REST API] ⇄ [Aiven MySQL]
```

---

## Technology Stack

### Backend

| Component       | Technology                        |
|-----------------|-----------------------------------|
| Framework       | Spring Boot 3, Spring Security    |
| Authentication  | JWT (JSON Web Tokens)             |
| Database        | MySQL (Aiven Cloud)               |
| API Design      | RESTful, Bean Validation          |
| Deployment      | Render Cloud                      |

### Frontend

| Component       | Technology                        |
|-----------------|-----------------------------------|
| Languages       | HTML,CSS, Javascript                       |
| Hosting         | Firebase Hosting                  |
| Domain          | [Here](https://dev16-blog.web.app) |

---

## Deployment & Access

- **Frontend:**  
  [![Firebase Frontend](https://img.shields.io/badge/Firebase-Frontend-FFCA28?style=for-the-badge&logo=firebase)](https://dev16-blog.web.app)

- **Backend:**  
  [![Render Backend](https://img.shields.io/badge/Render-Backend-46E3B7?style=for-the-badge&logo=render)](https://blog-1fcl.onrender.com/home)

- **User Access:**  
  [UI](https://dev16-blog.web.app)

---

## Core Features

### Administration

- Secure JWT-based authentication and authorization
- Dedicated admin dashboard for content and user management
- Role-based access control (RBAC)
- Automated email notifications on user registration

### User Experience

- Responsive, mobile-first UI
- Clean, accessible blog interface
- Real-time feedback and error handling

### Infrastructure

- Decoupled frontend/backend for independent scaling and deployment
- Managed MySQL database with automated backups (Aiven)
- Environment variable management for secure configuration

---

- Curious to know more about me visit here : [🌐](https://moneshgomo.netlify.web.app)

---
