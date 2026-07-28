# TaskFlow

A modern task management dashboard built with Flask and MySQL for assigning, tracking, and managing employee tasks.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?logo=mysql)

---

## ✨ Features

- 🔐 Secure Admin Login
- 📋 Assign, Update & Delete Tasks
- 👨‍💼 Employee Task Tracking
- 🔍 Search Tasks
- 📊 Dashboard Analytics
- ⚡ Task Priority Management
- 📅 Due Date Tracking
- 📱 Responsive UI

---

## 🛠️ Tech Stack

- Python
- Flask
- MySQL
- HTML5
- CSS3
- Bootstrap Icons

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/<YOUR_USERNAME>/task-management.git
```

### 2. Install dependencies

```bash
pip install flask flask-mysqldb
```

### 3. Import the database

Import the provided `database.sql` file into MySQL.

### 4. Configure MySQL

Update the database credentials in `app.py`.

```python
app.config["MYSQL_HOST"] = "localhost"
app.config["MYSQL_USER"] = "root"
app.config["MYSQL_PASSWORD"] = "YOUR_PASSWORD"
app.config["MYSQL_DB"] = "task_management"
```

### 5. Run the project

```bash
python app.py
```

### 6. Open in Browser

```
http://127.0.0.1:5000
```

---

## 🔑 Default Login

| Username | Password |
|----------|----------|
| admin | admin123 |

---

## 📂 Project Structure

```text
task-management/
│
├── app.py
├── database.sql
├── static/
├── templates/
└── README.md
```

---

## 👤 Author

**Krish Sachan**

- **Registration Number:** 23BET10033
- **Enrollment Number:** IN26010941
- **University:** VIT Bhopal University
- **Program:** B.Tech Computer Science and Engineering (Educational Technology)
- **Email:** krish.23bet10033@vitbhopal.ac.in

---

⭐ If you found this project useful, consider giving it a star on GitHub!
