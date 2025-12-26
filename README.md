# Multi-Tenant SaaS Backend

## Overview
This is a multi-tenant SaaS backend developed using Node.js, Express, and PostgreSQL.

Each tenant (company) has full data isolation on both the middleware and database side.
# Features
- Tenant registration and login
-- JWT-based authentication
- Role-based Access Control (Tenant Admin, User)
- Tenant isolation
- User Management
- Project management

- Task management
- Maximums per tenant (users, projects)
## Tech Stack
Node.js
Express.js
- PostgreSQL

– JWT
- bcrypt
- Docker (PostgreSQL)
## Architecture

*   Authentication using JWT
     {
- Tenant context based solely on token
• Middleware-implemented tenant isolation
- With foreign keys and indexes in PostgreSQL

## API Modules
In order

- Author & Tenant
- Users
- Projects - Tasks ## How to Run Locally ### 1. Start PostgreSQL (Docker) ``` docker-compose up -d