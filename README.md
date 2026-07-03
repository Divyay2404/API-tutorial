# 🍹 Flask REST API - Drinks Management

A simple RESTful API built with **Flask**, **Flask-SQLAlchemy**, and **SQLite** that performs CRUD operations on a drinks database. The project also demonstrates how to consume data from the **Stack Exchange API**.

---

## 🚀 Features

- Create a new drink
- Retrieve all drinks
- Retrieve a drink by ID
- Update drink details
- Delete a drink
- SQLite database integration
- RESTful API architecture
- JSON request and response handling
- API testing using Postman
- Stack Exchange API integration

---

## 🛠 Tech Stack

- Python 3
- Flask
- Flask-SQLAlchemy
- SQLite
- Postman
- REST API
- JSON

---

## 📁 Project Structure

```
project/
│
├── application.py
├── requirements.txt
├── drinks.db
├── README.md
└── .venv/
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/flask-drinks-api.git
```

### 2. Navigate to the project

```bash
cd flask-drinks-api
```

### 3. Create a virtual environment

```bash
py -m venv .venv
```

### 4. Activate the virtual environment

**Windows**

```bash
.venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
flask run
```

Server will start on

```
http://127.0.0.1:5000/
```

---

## 📌 API Endpoints

### Get all drinks

```
GET /drinks
```

### Get a drink by ID

```
GET /drinks/<id>
```

### Add a new drink

```
POST /drinks
```

Example JSON

```json
{
    "name": "Cola",
    "description": "Delicious"
}
```

### Update a drink

```
PUT /drinks/<id>
```

### Delete a drink

```
DELETE /drinks/<id>
```

---

## 🌐 Stack Exchange API

This project also demonstrates consuming data from the Stack Exchange API using HTTP requests and processing JSON responses.

Example:

- Fetch Stack Overflow questions
- Parse JSON responses
- Display useful information

---

## 🧪 Testing

The API endpoints were tested using **Postman**.

Operations tested:

- GET
- POST
- PUT
- DELETE

---

## 📚 What I Learned

- Building REST APIs using Flask
- CRUD operations
- SQLAlchemy ORM
- SQLite database management
- JSON serialization
- HTTP methods
- API testing with Postman
- Working with external APIs
- Error handling and debugging

---

## 🚀 Future Improvements

- User authentication using JWT
- Input validation
- Pagination
- Search and filtering
- Docker support
- Unit testing
- Deployment on Render or Railway
- API documentation using Swagger/OpenAPI

---

## 👨‍💻 Author

**Divyay Agarwal**

GitHub: https://github.com/Divyay2404

---

⭐ If you found this project useful, consider giving it a star!
