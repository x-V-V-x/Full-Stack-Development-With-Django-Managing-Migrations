Django Full-Stack Trading Bot Project

Overview
This project is a 2-hour guided full-stack web application built using the Django framework. The main focus is on Django migrations to define and manage database structures. Instead of emphasizing frontend templates, this project dives deep into the backend, providing a solid foundation for handling real-world data structures.



Project Goal
The mission is to develop a proof of concept (PoC) for an investment product that helps non-investors understand currency exchange. The bot automatically monitors exchange rates between two currencies and executes a transaction when the rate reaches a favorable threshold—mimicking real-world currency exchange companies.



Project Scope
Develop a Minimal Viable Product (MVP) for the trading bot
Implement Django migrations (including an empty migration with pre-inserted data)
Roll back migrations in case of issues
Render a real-time portfolio balance dashboard
Tech Stack
Backend: Django (Python)
Database: SQLite (or PostgreSQL/MySQL)
Frontend: Basic HTML (for admin UI)
API Integration: Exchange rate API
Prerequisites
To follow this project smoothly, you should have:
Basic knowledge of Python
Familiarity with Relational Databases (SQL, ORM)
Some exposure to HTML
Setup Instructions

1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/rameshwar-p001/Django-full-stack-develpment-project-main-clg.git

cd Django-full-stack-develpment-project-main-clg


2️⃣ Create a Virtual Environment
sh
Copy
Edit
python -m venv env

source env/bin/activate  # macOS/Linux

env\Scripts\activate  # Windows

3️⃣ Install Dependencies
sh
Copy
Edit
pip install -r requirements.txt

4️⃣ Apply Migrations
sh
Copy
Edit
python manage.py makemigrations
python manage.py migrate

5️⃣ Run the Server
sh
Copy
Edit
python manage.py runserver
Access the application at http://127.0.0.1:8000/


Done By :-    
         Rameshwar Digambar Patil

Div - J - 01

Pimpri Chinchwad University

Guided by :- Mr. Chandan Prasad

Faculty Guided :-Mrs. Ruchira Karanjikar
