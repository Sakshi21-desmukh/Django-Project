# Student Management System (Django)

## 📌 Project Description
This is a Student Management System built using Django.  
The project allows authenticated users to manage student records with full CRUD functionality, search, pagination, and admin customization.

---

## 🚀 Features
- User Registration, Login, and Logout
- Authentication using Django auth system
- Add, Edit, View, and Delete Students
- Search students by name and course
- Pagination (5 students per page)
- Server-side form validation
- Only logged-in users can manage students
- Only superusers can delete student records
- Django Admin customization

---

## 🛠 Technologies Used
- Python 3
- Django 6.0.3
- SQLite (default database)
- HTML (Django Templates)

---

## 📂 Project Structure
Django assisment/
│
├── manage.py
├── db.sqlite3
├── requirements.txt
├── README.md
│
├── student_project/
│ ├── settings.py
│ ├── urls.py
│ └── ...
│
├── students/
│ ├── models.py
│ ├── views.py
│ ├── forms.py
│ ├── urls.py
│ └── admin.py
│
└── templates/
├── base.html
├── registration/
│ ├── login.html
│ └── register.html
└── students/
├── student_list.html
├── student_form.html
└── student_confirm_delete.html


