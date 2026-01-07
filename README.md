

Expense Tracker – Django Web Application

Project Overview

Expense Tracker is a web-based application developed using **Django** that helps users record, manage, and analyze their daily expenses efficiently.
The system allows users to **add, view, filter, update, and delete expenses** through a clean and user-friendly interface.

This project aims to promote **better financial awareness** by providing a simple yet effective way to track spending habits.

---

 Objectives of the Project

* To help users track daily expenses digitally
* To categorize expenses for better understanding
* To provide a secure login and user-based data access
* To display expense summaries clearly
* To simplify expense management using a web interface

---

 Technologies Used

* **Frontend:** HTML, Tailwind CSS
* **Backend:** Python, Django Framework
* **Database:** SQLite (default Django database)
* **Tools:** VS Code, Git, Web Browser

---

Features

* User Registration and Login (Authentication)
* Secure Logout
* Add new expenses with:

  * Title
  * Amount
  * Category
  * Date
* View all expenses in a table format
* Filter expenses by category
* Update existing expenses
* Delete expenses
* Dashboard with:

  * Total expense amount
  * Total number of entries
  * Expense history
* Responsive and modern UI design



Project Structure

Expense_Tracker/
│
├── expense_tracker/        # Main project settings
├── expenses/               # App containing models, views, urls
├── templates/              # HTML templates
│   ├── login.html
│   ├── register.html
│   ├── home.html
│   └── dashboard.html
├── db.sqlite3              # Database
├── manage.py
└── README.md




 Create Virtual Environment


python -m venv myenv


Activate the environment:

**Windows**


myenv\Scripts\activate






Run Database Migrations

python manage.py makemigrations
python manage.py migrate


Create Superuser (Optional)

python manage.py createsuperuser


Start the Server

python manage.py runserver


Open browser and go to:


http://127.0.0.1:8000/




* New users must **register**
* Registered users can **log in**
* Each user can access **only their own expenses**
* Secure logout functionality is provided



The dashboard displays:

* Total expenses
* Total number of entries
* Expense list with edit and delete options
* Category-based filtering

This helps users analyze their spending easily.



* Monthly and yearly expense reports
* Graphical charts for expense analysis
* Export expenses as PDF or Excel
* Budget limit alerts
* Multi-currency support



* Hands-on experience with Django framework
* Understanding of MVC/MVT architecture
* User authentication and authorization
* CRUD operations
* Frontend-backend integration
* Database handling using ORM



Developed By

Swathi Dinesh
B.Tech – Computer Science Engineering







