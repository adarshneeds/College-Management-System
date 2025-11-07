# 🎓 College Management System

A **College Management System** built using the **Django Framework**, designed to streamline interactions between **students**, **teachers**, and **administrators**.  
The system efficiently manages attendance, marks, timetables, and academic records to simplify college operations.

---

## ⚙️ Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript (Django Templates)
- **Database:** SQLite (default)
- **Server:** Django Development Server

---

## 🚀 Features
- Unified login system for Students and Teachers  
- Attendance management  
- Marks and performance tracking  
- Timetable management  
- Admin dashboard for full control  
- Attendance period reset via Admin Panel  

---

## 🧩 Installation
Make sure Python and Django are installed.

```bash
pip install django
````

---

## ▶️ Usage

1. Navigate to the project folder:

   ```bash
   cd College-Management-System
   ```
2. Run the Django server:

   ```bash
   python manage.py runserver
   ```
3. Open your browser and visit:
   **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**

---

## 🔑 Login Details

The login page is common for both students and teachers.

| User Type | Username  | Password     |
| --------- | --------- | ------------ |
| Student   | `samarth` | `project123` |
| Teacher   | `trisila` | `project123` |

---

### 🧭 Django Admin Access

Visit **[http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)**

| Username | Password     |
| -------- | ------------ |
| `admin`  | `project123` |

Create a new superuser:

```bash
python manage.py createsuperuser
```

---

## 🧱 User Management

* Add new **students** and **teachers** from the Django Admin panel.
* Modify data such as **Departments**, **Courses**, **Classes**, and **Attendance**.
* Admins have full access to update and maintain records.

> 📘 For detailed documentation, refer to the included project report.


## 🧑‍🏫 Teacher Portal Screens

![Attendance Overview](https://imgur.com/4Rl7Fpv.png)

---

## 🧑‍🎓 Student Portal Screens

![Attendance Tracker](https://imgur.com/fu7gxk8.png)

---

## 🛠️ Admin Dashboard Screens

![Admin Home](https://imgur.com/sDvDc9N.png)
![Database Models](https://imgur.com/tMKWx6f.png)
![Admin Panel View](https://imgur.com/PvCsNeB.png)

---


## 🧾 Directory Structure
````
College-Management-System/
│
├── manage.py
├── db.sqlite3
├── college/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── info/
│   ├── models.py
│   ├── views.py
│   ├── admin.py
│   ├── forms.py
│   └── templates/
│       ├── student/
│       ├── teacher/
│       └── admin/
│
└── static/
    ├── css/
    ├── js/
    └── images/
