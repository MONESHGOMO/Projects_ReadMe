# 🚀 Authentication and Authorization Using Spring Security

This micro-project demonstrates robust authentication and authorization mechanisms using Spring Security, with a focus on role-based access control and secure API endpoints.

---

## Key Features

- **User Registration:**  
  Register new users with designated roles (`USER` or `ADMIN`).

- **Role-Based Access Control:**  
  - **USER:** Access to user-specific pages.
  - **ADMIN:** Access to both user and admin pages.

- **Secure Endpoints:**  
  All routes are protected and accessible only to authenticated and authorized users.

---

## Tech Stack

- **Java 17**
- **Spring Boot 3**
- **Spring Security**
- **PostgreSQL**

---

## API Endpoints

| Action           | Method | Endpoint         | Description                       |
|------------------|--------|------------------|-----------------------------------|
| Register User    | POST   | `/register/user` | Register a new user               |
| Login            | POST   | `/login`         | Authenticate and receive a token  |
| General Home     | GET    | `/home`          | Public/general access             |
| User Home        | GET    | `/user/home`     | Accessible to users with `USER`   |
| Admin Home       | GET    | `/admin/home`    | Accessible to users with `ADMIN`  |

---

Checkout the posts 
 <p >
  <a href="https://www.linkedin.com/posts/moneshgomo_authentication-and-authorization-using-activity-7291567908969738240-Qe6g?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFFNxJwB2y_FPVz8VbNICeIbR-SrLUaz5K4">
    <img src="https://skillicons.dev/icons?i=linkedin" />
  </a>
</p>

[![YouTube Demo](https://img.icons8.com/color/48/youtube-play.png)](https://www.youtube.com/watch?v=7OLQLpiSuDQ)


```JAVA
class Main {
    public static void main(String args[]) {
        System.out.println("I built this project to understand how Spring Security works and how to implement it in my applications");
    }
}
```
