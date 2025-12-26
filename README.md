# Multi-Tenant SaaS Application

A full stack, Dockerized **Multi-Tenant SaaS Application** with tenant isolation capability, JWT login, Role-Based access control, with full user/project/task management.

This project illustrates real-world implementation of SaaS architecture where several tenants use a common system and isolate their data completely.

---

## ???? Tech Stack

Blog

### Backend
Node.js
- Express.js
- PostgreSQL
- JWT Authentication

- bcrypt (Password Hashing)
### Frontend
- React (Vite)

- React Router
- Fetch API

# Infrastructure
Infrastructure

- Docker

- Docker Compose
---

## ✨ Features
Features
- ???? **Multi-Tenant Architecture
- Each tenant is represented by a distinct subdomain

- Complete Tenant Level Data Isolation
- ???? **Authentication & Authorization**

- JWT认证
- Role-based access (`tenant_admin`, `user

• Bcrypt hashing of passwords
- ????  **User Management**

- Tenant admin can create users
- Users are exclusive to one tenant

- ???? **Project Management**

- Projects creation and view as per tenant - Projects are separate in each tenancy - ✅ Task Management - "Tasks belong to projects" - It is tenant-specific. - ???? **Fully Dockerized – Frontend, backend, and database are running in containers - Single-command startup with Docker Compose --- ## ???? Folder Structure