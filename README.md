# Subscription Management System

React + ASP.NET Core | Full-Stack Demo Project

A production-style multi-tenant SaaS admin application built using React (TypeScript) and ASP.NET Core Web API.
This project demonstrates real-world architecture, security, and scalability practices used in modern SaaS products.

🎯 Purpose: Portfolio & freelance demo for global clients
👨‍💻 Role: Full-Stack Developer (Backend + Frontend + Cloud)

✨ Features
🔐 Authentication & Authorization

JWT-based authentication

Role-based access control (Admin / Manager / User)

Protected API endpoints & frontend routes

🏢 Organization & User Management

Multi-tenant organization support

Invite users & assign roles

Activate / deactivate users

💳 Subscription & Plan Management

Create subscription plans (Free / Pro / Enterprise)

Assign plans to organizations

Expiry & status tracking (Active / Expired / Suspended)

📊 Dashboard & Reporting

Active users & subscriptions

Expired plans

Recent system activity

🧾 Audit Logs

User login history

Subscription changes

Administrative actions

🛠️ Tech Stack
Frontend

React 18

TypeScript

Material UI (MUI)

React Router

Axios / React Query

Backend

ASP.NET Core Web API (.NET 7/8)

Entity Framework Core

JWT Authentication

Clean architecture (Controllers, Services, Repositories)

Database

SQL Server (Azure SQL compatible)

Cloud & DevOps

Azure App Service

Azure SQL Database

Swagger (OpenAPI)

🏗️ Architecture Overview
Backend Structure
API
├── Controllers
├── Services
├── Repositories
├── Domain
├── DTOs
├── Middleware
└── Infrastructure

Frontend Structure
src
├── components
├── pages
├── services
├── hooks
├── context
├── routes
└── utils

🔗 API Endpoints (Sample)
POST   /api/auth/login
POST   /api/auth/register
GET    /api/dashboard/summary
POST   /api/organizations
POST   /api/subscriptions
GET    /api/audit-logs


Swagger UI available for full API documentation.

📸 Screenshots

(Add screenshots here)

Login

Admin Dashboard

User Management

Subscription Plans

Audit Logs

☁️ Live Demo

🔗 Frontend: (Add Azure Static Web App URL)
🔗 API: (Add Azure App Service URL)

⚙️ How to Run Locally
Prerequisites

.NET 7 or 8 SDK

Node.js 18+

SQL Server

Backend
cd api
dotnet restore
dotnet run

Frontend
cd client
npm install
npm start


Frontend runs on http://localhost:3000
API runs on https://localhost:5001

🔐 Environment Variables
Backend
ConnectionStrings__DefaultConnection
Jwt__Key
Jwt__Issuer
Jwt__Audience

Frontend
REACT_APP_API_BASE_URL

🎯 What This Project Demonstrates

Real-world SaaS architecture

Secure authentication & authorization

Clean API design

Modern React practices

Cloud-ready deployment

📌 Future Enhancements

Payment gateway integration (Stripe)

Refresh tokens

Docker support

API versioning

Email notifications

👨‍💻 Author

Hariom Yadav
Senior .NET Full-Stack Developer
ASP.NET Core | React | Azure

Available for freelance & remote projects

⭐ Feedback

If you find this project useful, feel free to ⭐ the repo or connect with me.
