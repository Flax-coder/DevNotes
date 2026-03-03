# DevNotes

![Java](https://img.shields.io/badge/Java-21-red)
![Spring Boot](https://img.shields.io/badge/SpringBoot-4-brightgreen)
![Angular](https://img.shields.io/badge/Angular-17-red)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

A role-based publishing platform built with Spring Boot and Angular, implementing secure authentication, article workflow and object storage.

🚀 Overview

DevNotes is a role-based publishing platform that allows users to create, review and manage technical articles.

The project implements secure authentication, role-based authorization, article workflow management and external object storage.

## 🛠 Tech Stack

- Java 21
- Spring Boot 4
- Spring Security + JWT
- Angular 17
- MySQL
- Docker + MinIO

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
