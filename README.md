# Django To-Do List Application

A simple To-Do List application built using **Django (backend)** and **HTML/CSS (frontend)**.  
This app allows users to manage their daily tasks with authentication support and task tracking.

---

## Features

1. **User Authentication**
   - Signup, Login, and Logout functionality.
   - Username, Email, and Password required during registration.
   - Checks if the chosen username already exists in the database.

2. **Task Management**
   - Create, Update/Edit, and Delete tasks.
   - Mark tasks as complete or incomplete.
   - User-specific task storage using SQLite3 database.

3. **Database**
   - SQLite3 is used to store user accounts and their tasks.

4. **Future Enhancements**
   - Password reset/retrieve via email.

---

## Tech Stack

- **Backend:** Django, JS
- **Frontend:** HTML, CSS
- **Database:** SQLite3

---

## Installation
1. Clone the repository: https://github.com/Hikey908/To-Do-Application.git
2. Navigate into the project directory: cd todo
3. Run database migrations: python manage.py migrate
4. Start the development server: python manage.py runserver
5. Open the app in your browser at: http://127.0.0.1:8000/

---

## Screenshots
<p align="center">
  <img width="530" height="710" alt="image" src="https://github.com/user-attachments/assets/77a2d84c-8c41-4856-af5d-fb96a34174d1" />
</p>

---

## Acknowledgements

This project is a copy of the original project available at:  
https://github.com/Err0r-By-Night/Todo_app_using_django

I created this version for **practice purposes** while learning Django.  

---

### Changes Made
1. Added validation to check if the username already exists in the database.
2. Fixed routing issues while moving from login page to signup page.  
