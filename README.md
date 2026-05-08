# 📝 To Do App Backend (Django REST Framework)

A fully functional **To Do App Backend API** built using **Django** and **Django REST Framework (DRF)**.  
This project provides APIs for managing tasks with complete CRUD operations and can be connected easily with any frontend like React, Angular, or Flutter.

---

# 🚀 Features

- User Authentication
- Create Tasks
- Update Tasks
- Delete Tasks
- Mark Tasks as Completed
- RESTful APIs
- SQLite Database
- Django Admin Panel
- Clean Project Structure

---

# 🛠️ Tech Stack

- Python
- Django
- Django REST Framework
- SQLite
- Postman (for API Testing)

---

# 📂 Project Structure

```bash
to_do_app_backend/
│── manage.py
│── requirements.txt
│── db.sqlite3
│── README.md
│
├── backend/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
├── todo/
│   ├── models.py
│   ├── views.py
│   ├── serializers.py
│   ├── urls.py
│   ├── admin.py
│   └── migrations/
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/abhishek888bhatt-max/to_do_app_backend.git
```

## 2️⃣ Move Into Project Directory

```bash
cd to_do_app_backend
```

## 3️⃣ Create Virtual Environment

```bash
python -m venv venv
```

## 4️⃣ Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

---

# 📦 Install Dependencies

```bash
pip install -r requirements.txt
```

If requirements.txt is not available:

```bash
pip install django djangorestframework
```

---

# 🔄 Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

# 👤 Create Superuser

```bash
python manage.py createsuperuser
```

---

# ▶️ Run Server

```bash
python manage.py runserver
```

Server will start at:

```bash
http://127.0.0.1:8000/
```

---

# 📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/tasks/` | Get all tasks |
| POST | `/tasks/` | Create new task |
| PUT | `/tasks/id/` | Update task |
| DELETE | `/tasks/id/` | Delete task |

---

# 🧪 API Testing

You can test APIs using:

- Postman
- Thunder Client
- Insomnia

---

# 🔐 Authentication

This project supports Django authentication system.

Example routes:

```bash
/login/
/logout/
/admin/
```

---


---

# 🌟 Future Improvements

- JWT Authentication
- Pagination
- Search & Filter
- Deployment on Render/Heroku
- Docker Support

---

# 👨‍💻 Author

## Abhishek Bhatt

GitHub: https://github.com/abhishek888bhatt-max
