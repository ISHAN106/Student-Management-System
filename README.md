# Student-Management-System
A web-based application for managing student records, attendance, and departmental information, built with Flask and MySQL.

This system provides user authentication, allowing users to sign up, log in, and log out securely. It enables administrators to add, edit, and view student details, manage department information, and track student attendance efficiently.

The backend is powered by Flask, using Flask-Login for authentication and Flask-SQLAlchemy for ORM-based database management. The application integrates with a MySQL/MariaDB database, and HTML templates are rendered using Flask for the web interface. Flash messaging is used throughout the app to provide user feedback on actions.

To set up the project, clone the repository, install the dependencies listed in requirements.txt, and configure your MySQL database connection in main.py. Once the setup is complete, run the application with python main.py and access the web interface to manage students and departments.

Database models for students, departments, attendance, and users are defined in main.py. An example SQL schema is also provided in students.sql to help you initialize your database.

This project is made by Ishan and Naveen.


