# Internship Management System

A full-stack Internship Management System built with Angular, Flask, and AWS DynamoDB. This platform helps students browse and apply for internships, employers to manage listings and applications, and administrators to oversee the entire process.

## 🛠️ Tech Stack

- **Frontend:** Angular
- **Backend:** Python (Flask)
- **Database:** AWS DynamoDB
- **Architecture:** REST API, Role-Based Access Control (RBAC)

## 🔐 User Roles

- **Student:** Browse internships, apply, upload CVs, and submit reviews.
- **Employer:** Post internships, review applications, and respond to reviews.
- **Admin:** Manage users and moderate reviews.

## 🚀 Features

- User registration and login (role-based)
- Internship listings with pagination
- Internship application with document uploads (CV/Transcript)
- Email notifications (for application updates)
- Review and feedback system
- Admin moderation tools

## 📁 Project Structure

```bash
internship-management-system/
├── backend/              # Flask API
│   └── app.py
|___
├── frontend/             # Angular App
│   └── internship-ui/
├── README.md
