📘 Django Blog Application








A modern, full-featured blog platform built with Django. This project demonstrates real-world web development concepts including authentication, database relationships, CRUD operations, and dynamic content rendering.

🌐 Live Demo

🚧 Coming Soon
(You can deploy using platforms like Render, Railway, or PythonAnywhere)

🚀 Overview

This is a practice-based full-stack web application designed to simulate a real-world blogging platform. It enables users to create, manage, and interact with content in a structured and scalable way.

The project focuses on both backend logic and frontend presentation, making it ideal for learning, portfolio showcasing, and interview preparation.

✨ Features

🔐 Authentication & Authorization

User registration, login, and logout.
Protected routes using authentication decorators.

📝 Blog Post Management (CRUD)

Create, read, update, and delete blog posts.
Access restricted to authenticated users.

🗂️ Categories & Tags

Structured categorization of posts.
Flexible tagging system (Many-to-Many relationship).

💬 Comment System

Add and view comments on blog posts.
Enhances user interaction.

🔎 Search Functionality

Search posts by title and content.
Improved content discoverability.

📄 Pagination

Efficient navigation through large datasets.

🎨 Responsive UI

Built with Bootstrap.
Clean and mobile-friendly design.

⚙️ Admin Panel

Manage posts, users, categories, tags, and comments via Django admin.

🛠️ Tech Stack

Category	Technology.
Backend	Django, Python.
Frontend	HTML, CSS, Bootstrap.
Database	SQLite / MySQL.
ORM	Django ORM.

📂 Project Structure (Simplified)

blog_project/
│── blog/                # Main app
│── templates/           # HTML templates
│── static/              # CSS, JS, assets
│── db.sqlite3           # Database
│── manage.py


⚡ Getting Started

1️⃣ Clone Repository.

git clone https://github.com/fahmidprachaw/Amar_Blogs
cd django-blog.

2️⃣ Create Virtual Environment

python -m venv venv.
3️⃣ Activate Environment

venv\Scripts\activate      # Windows
source venv/bin/activate   # Linux/Mac

4️⃣ Install Dependencies.

pip install -r requirements.txt.

5️⃣ Run Migrations

python manage.py migrate.

6️⃣ Create Superuser

python manage.py createsuperuser.

7️⃣ Start Server

python manage.py runserver.

📚 Key Learning Outcomes

Django project architecture and app structuring.
Model relationships (ForeignKey, ManyToManyField).
Authentication and authorization system.
CRUD operations with class-based / function-based views.
Template rendering with Django Template Language (DTL).
Form handling using ModelForms.
Pagination and search implementation.

🔮 Future Improvements

👤 User profile system.
👍 Like / Dislike functionality.
🔗 Social media sharing.
🌐 REST API with Django REST Framework.
☁️ Deployment (Docker + CI/CD).

📸 Screenshots

🚧 Add screenshots here (Home, Blog Detail, Admin Panel, etc.)

📌 Purpose

This is a practice project built to strengthen full-stack development skills using Django. It reflects real-world application structure and is suitable for portfolio, academic, and learning purposes.

📄 License

This project is licensed under the MIT License.

🙌 Acknowledgment

Built as part of continuous learning and hands-on practice in modern web development.
