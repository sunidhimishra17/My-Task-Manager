# My-Task-Manager

A full-stack task management web application built with Python (Django REST Framework) and React.js, featuring secure authentication and interactive CRUD operations.

A robust, enterprise-grade Task Management Web Application designed to streamline workflows and track daily activities. This project features a secure, scalable Django REST Framework (DRF) backend paired with an interactive, responsive React.js frontend. 

## Key Features

1. Full CRUD Operations: Seamlessly Create, Read, Update, and Delete tasks with real-time state updates.

2. Task Status Tracking: Categorize tasks based on their current state (e.g., Pending, In Progress, Completed).
 
3. Responsive UI: A clean, mobile-friendly interface built with modern UI principles.
 
4. RESTful API Architecture: Clean separation of concerns between backend services and frontend presentation.
 
5. Robust Exception Handling: Graceful error catching on both server and client sides to ensure a smooth user experience.

## Tech Stack

Frontend

1. React.js (Functional Components, Hooks)

2. Axios (Promise-based HTTP client for API requests)

3. HTML5 & CSS3 / Tailwind CSS (Modern responsive styling)

Backend

1. Python 3

2. Django & Django REST Framework (DRF) (API development and serialization)

3. SQLite / PostgreSQL (Relational database mapping)

## Project Architecture

text ...

    ├── backend/               # Django Backend Application
    │   ├── manage.py          # Django CLI utility
    │   ├── core/              # Main project configuration (settings, URLs)
    │   └── api/               # Task application (models, views, serializers)
    │
    ├── frontend/              # React Frontend Application
    │   ├── public/            # Static assets
    │   └── src/               # React components, styles, and API routing
    └── README.md

## Prerequisites 

1. Python installed

2. Node.js installed

3. Git installed

## Steps 

Step 1: Clone and Set Up the Repository

Clone this repository:

    git clone [https://github.com/sunidhimishra17/My-Task-Manager.git](https://github.com/sunidhimishra17/My-Task-Manager.git)

Navigate into the project root:

    cd My-Task-Manager

Step 2: Backend Setup (Django)

Navigate to the backend directory:

    cd backend

Create a virtual environment:

    python -m venv venv

Activate the virtual environment

On Windows:

    venv\Scripts\activate

On macOS/Linux:

    source venv/bin/activate

Install backend dependencies

    pip install -r requirements.txt

Run migrations to set up the database

    python manage.py migrate

Start the Django development server

    python manage.py runserver

Step 3: Frontend Setup (React)

Open a new terminal window/tab:

Navigate to the frontend directory:

    cd frontend

Install npm packages:

    npm install

Start the React development server:

    npm start

## API Endpoints Reference

The backend exposes the following clean RESTful routes for interaction:

1. HTTP Method-> Endpoint -> Description

2. GET-> /api/tasks/-> Fetch all tasks 

3. POST-> /api/tasks/-> Create a new task

4. GET-> /api/tasks/<id>/-> Fetch details of a specific task

5. PUT/PATCH-> /api/tasks/<id>/-> Update an existing task

6. DELETE-> /api/tasks/<id>/-> Delete a specific task
