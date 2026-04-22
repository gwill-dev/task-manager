<img width="935" height="340" alt="Screenshot 2026-04-22 114718" src="https://github.com/user-attachments/assets/31637740-fa8f-483e-bee7-74e051a672e4" />
# 📝 Task Manager (Django CRUD App)

A simple and modern Task Manager web application built with Django.
This app allows users to create, manage, update, and delete tasks through a clean and responsive interface.

---

## 🚀 Features

* ✅ Create new tasks
* 📋 View all tasks
* ✏️ Edit existing tasks
* ✔️ Mark tasks as completed
* ❌ Delete tasks
* 🎨 Responsive UI using Bootstrap
* 💾 Persistent data storage with SQLite

---

## 🛠️ Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS, Bootstrap
* **Database:** SQLite
* **Version Control:** Git & GitHub

---

## 📂 Project Structure

```
taskmanager/
│── taskmanager/        # Main project settings
│── tasks/              # App for task management
│    ├── templates/
│    │     └── tasks/
│    │           ├── home.html
│    │           └── edit.html
│    ├── models.py
│    ├── views.py
│    ├── urls.py
│── db.sqlite3
│── manage.py
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/your-username/task-manager.git
cd task-manager
```

### 2. Create virtual environment

```
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3. Install dependencies

```
pip install django
```

### 4. Apply migrations

```
python manage.py makemigrations
python manage.py migrate
```

### 5. Run the server

```
python manage.py runserver
```

---

## 🌐 Usage

Open your browser and go to:

```
http://127.0.0.1:8000/
```

---

## 🔐 Admin Panel

Create a superuser:

```
python manage.py createsuperuser
```

Then access:

```
http://127.0.0.1:8000/admin/
```

---

## 📸 Screenshots

*(Add screenshots here later)*

---

## 📈 Future Improvements

* User authentication (login/signup)
* Task categories & priorities
* REST API (Django REST Framework)
* Drag-and-drop task management
* Deployment (Render / Railway)

---

## 👨‍💻 Author

**Amadi Uchechukwu Godswill**

* GitHub: https://github.com/your-username
* LinkedIn: https://www.linkedin.com/in/your-linkedin

---

## 📄 License

This project is open-source and available under the MIT License.

