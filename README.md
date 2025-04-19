# JOB VAULT 🗃️  
**Job Offer Management System with Automated Selection Processes**  

A backend application for managing job portals, enabling companies to post offers, candidates to apply, and automated CV-job matching.  

---

## 🎯 Description  
**Job Vault** is a backend system designed to streamline job offer management, applications, and automated candidate selection. Features include:  
- **Companies** can publish/manage job offers.  
- **Candidates** can apply, upload CVs, and track application statuses.  
- **Automated nightly batch processing** for CV-offer matching.  
- Secure authentication via **JWT** and **OAuth2** (Google/GitHub).  
- Persistent sessions for authenticated users.  
- Full **Swagger UI** API documentation.  
- MariaDB integration via JPA/Hibernate.  

---

## 🧩 Technologies  
| Technology           | Use Case                              |  
|----------------------|---------------------------------------|  
| Spring Boot          | Core application framework            |  
| JWT + OAuth2         | Authentication (Token + Social Login) |  
| Spring Security      | Route protection                      |  
| MariaDB + JPA        | Persistence layer (Jobs, Users, CVs)  |  
| Hibernate            | ORM for database operations           |  
| Spring Batch         | Nightly CV-job matching               |  
| Spring Session       | Persistent user sessions              |  
| Swagger/OpenAPI      | Interactive API documentation         |  
| JUnit + Mockito      | Unit & integration testing            |  

---

## ⚙️ Key Features  
- **Auth & Roles**  
  - JWT-based registration/login.  
  - OAuth2 login via Google/GitHub.  
  - Role-based access control (Admin, Company, Candidate).  
- **Job Management**  
  - CRUD operations for job offers.  
  - Applications with PDF attachments.  
- **Automation**  
  - Nightly batch job to match CVs with offers.  
  - Email notifications for matches.  
- **Security**  
  - Protected API endpoints.  
  - Persistent sessions via Spring Session.  
- **API Docs**  
  - Interactive Swagger UI at `/swagger-ui.html`.  

---


