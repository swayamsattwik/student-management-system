# CampusDesk — Student Management System
Original full-stack project built with React, Express and MySQL.

## Features
- Admin sign-in with JWT
- Student create, search, edit and delete
- Daily attendance marking (Present / Absent / Late)
- Dashboard statistics
- Responsive light dashboard

## Run locally
1. Install Node.js 20+ and MySQL 8+.
2. Create database: `CREATE DATABASE student_management;`
3. Import `backend/schema.sql` into MySQL.
4. In `backend`, run `cp .env.example .env`, fill in DB settings, then `npm install && npm run dev`.
5. In `frontend`, run `cp .env.example .env`, then `npm install && npm run dev`.
6. Open http://localhost:5173.

Initial local admin credentials: `admin@campus.local` / `ChangeMe123!`. Change these environment values before deployment.

## Deployment
Deploy backend as a Node web service and frontend as a static site. Use a managed MySQL database. Set backend environment variables from `backend/.env.example`; set frontend `VITE_API_URL` to the backend URL ending in `/api`. Import `backend/schema.sql` into the hosted database.

Customize, run and test this project before listing it on a resume.
# student-management-system
