# My-Task-Manager

A full-stack task management web application built with Python (Django REST Framework) and React.js, featuring secure authentication and interactive CRUD operations.

A robust, enterprise-grade Task Management Web Application designed to streamline workflows and track daily activities. This project features a secure, scalable Django REST Framework (DRF) backend paired with an interactive, responsive React.js frontend. 

## 🎯 Key Features

1. Full CRUD Operations: Seamlessly Create, Read, Update, and Delete tasks with real-time state updates.

2. Task Status Tracking: Categorize tasks based on their current state (e.g., Pending, In Progress, Completed).
 
3. Responsive UI: A clean, mobile-friendly interface built with modern UI principles.
 
4. RESTful API Architecture: Clean separation of concerns between backend services and frontend presentation.
 
5. Robust Exception Handling: Graceful error catching on both server and client sides to ensure a smooth user experience.

## 🛠️ Tech Stack

Frontend

1. React.js (Functional Components, Hooks)

2. Axios (Promise-based HTTP client for API requests)

3. HTML5 & CSS3 / Tailwind CSS (Modern responsive styling)

Backend

1. Python 3

2. Django & Django REST Framework (DRF) (API development and serialization)

3. SQLite / PostgreSQL (Relational database mapping)

## 🏗️ Project Architecture

```text
├── backend/               # Django Backend Application
│   ├── manage.py          # Django CLI utility
│   ├── core/              # Main project configuration (settings, URLs)
│   └── api/               # Task application (models, views, serializers)
│
├── frontend/              # React Frontend Application
│   ├── public/            # Static assets
│   └── src/               # React components, styles, and API routing
└── README.md
