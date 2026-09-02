Django Task Manager

A simple and user-friendly Task Manager web application built with Django.
The project allows users to create, view, edit, complete, and delete tasks through a clean web interface.

🚀 Features

- ➕ Add new tasks
- 📋 View all tasks
- ✏️ Edit existing tasks
- ✅ Mark tasks as completed
- 🗑️ Delete tasks
- 🔐 Django Admin panel for managing tasks
- 🎨 Custom CSS styling
- 💾 SQLite database
- 📱 Clean and simple web interface

🛠️ Technologies Used

- Python
- Django
- HTML5
- CSS3
- SQLite
- Git & GitHub

📂 Project Structure

TaskManager/
│
├── taskapp/
│   ├── migrations/
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── taskmanager/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── templates/
│   ├── base.html
│   ├── home.html
│   ├── add_task.html
│   └── edit_task.html
│
├── static/
│   └── css/
│       └── style.css
│
├── manage.py
├── .gitignore
└── README.md

⚙️ Installation & Setup

1. Clone the repository

git clone https://github.com/Malaika763/TaskManager.git

2. Create a virtual environment

python -m venv .venv

3. Activate the virtual environment

Windows:

.venv\Scripts\activate

4. Install Django

pip install django

5. Apply migrations

python manage.py migrate

6. Run the development server

python manage.py runserver

Then open:

http://127.0.0.1:8000/

🎯 Learning Goals

This project was created to practice and strengthen my understanding of:

- Django project and app structure
- Models and databases
- Django forms
- URL routing
- Views
- Templates
- CRUD operations
- Django Admin
- Static files and CSS
- Git and GitHub

👩‍💻 Author

Malaika Dawood

This project is part of my journey of learning Python, Django, and web development.
⭐ If you find this project useful or interesting, consider giving the repository a star!
