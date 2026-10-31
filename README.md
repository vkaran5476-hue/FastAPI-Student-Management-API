# FastAPI-Student-Management-API
A beginner-friendly Student Management REST API built with Python, FastAPI, and SQLite. It supports CRUD operations, data validation using Pydantic, and automatic API documentation with Swagger UI.
# Student Management API using FastAPI

Hi! 👋

This is a Python backend project I built while learning FastAPI and REST API development.

The goal of this project was to understand how backend applications handle student data, communicate through APIs, and store information in a database.

## 🚀 About the Project

The Student Management API allows users to manage student records through different HTTP requests.

I used FastAPI to build the API and SQLite to store student information.

## 🛠️ Technologies Used

- Python
- FastAPI
- SQLite
- Pydantic
- Uvicorn
- Requests

## ✨ Features

- Add a new student
- View all students
- Find a student using their ID
- Update student information
- Delete student records
- Validate incoming data
- Handle errors such as missing students and duplicate emails
- Interactive API documentation using Swagger UI

## 📁 Project Structure

```text
FastAPI-Student-Management-API/
│
├── main.py
├── fastapi_students.db
├── requirements.txt
└── README.md
```

The database file is created when the application runs. It does not need to be committed to GitHub.

## ⚙️ Installation and Setup

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**2. Move into the project folder**

```bash
cd FastAPI-Student-Management-API
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Start the application**

```bash
uvicorn main:app --reload
```

**5. Open API documentation**

Visit:

```text
http://127.0.0.1:8000/docs
```

## 📌 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | `/students` | Add a student |
| GET | `/students` | Get all students |
| GET | `/students/{student_id}` | Get student by ID |
| PUT | `/students/{student_id}` | Update student |
| DELETE | `/students/{student_id}` | Delete student |

## 📚 What I Learned

While building this project, I got practical experience with:

- Creating REST APIs using FastAPI
- Connecting Python applications with SQLite
- Working with HTTP methods
- Validating request data using Pydantic
- Handling API errors
- Testing API endpoints

This project is part of my journey toward becoming a Python Backend Developer. I'm also interested in exploring how FastAPI can be used to build AI-powered applications.

## 👨‍💻 About Me

**Karan Verma**

B.Tech Information Technology | 2026 Graduate

- GitHub: https://github.com/vkaran5476-hue
- LinkedIn: https://www.linkedin.com/in/karan-verma-83b1352aa/
- Portfolio: https://karan-verma-portfolio-8d05--bmpz.pepita.page

I'm continuously learning, building projects, and looking for opportunities in Python and Backend Development.

Thanks for visiting my project! ⭐
