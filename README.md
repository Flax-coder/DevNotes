DevNotes

Full-Stack editorial platform built with Spring Boot and Angular.

🚀 Overview

DevNotes is a role-based publishing platform that allows users to create, review and manage technical articles.

The project implements secure authentication, role-based authorization, article workflow management and external object storage.

🏗 Architecture

Backend: Spring Boot 4

Security: Spring Security + JWT

Frontend: Angular (Standalone SPA)

Database: MySQL

Storage: MinIO (S3-compatible)

Containerization: Docker Compose

The architecture follows separation between API and client application.

🔐 Authentication & Authorization

JWT-based authentication

Custom authentication filter

Role-based access control

Roles implemented:

Admin

Writer

Revisor

User

📦 Main Features

Article creation and editing

Article review workflow

Role management system

Image upload to object storage

Category management

Admin dashboard

Secure REST API

🖥 Project Structure

devnotes-api     → Spring Boot backend
devnotes-web     → Angular frontend

⚙️ Running the Project

Backend
cd devnotes-api
mvn spring-boot:run
Frontend
cd devnotes-web
npm install
ng serve
🧠 Learning Focus

This project focuses on:

Secure REST API design

Clean architecture principles

Role-based authorization

DTO mapping

Separation of concerns

State management in SPA

📌 Author

Flavio Trettenero
Full-Stack Developer
Java • Spring Boot • Angular

📄 License

MIT License
