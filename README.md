
# 📝 Task Management System (Django + DRF)

A **Task Tracking Web Application** built with **Django, Django REST Framework, TailwindCSS, and Chart.js**.  
This project allows users to manage personal tasks, share tasks with other users, track progress, and view analytics.

---

## 🚀 Features
- 🔑 User Authentication (Register/Login/Logout)
- ✅ Create, Update, Delete, and View Tasks
- 📂 File Upload Support for Tasks
- 👥 Share Tasks with Other Users
- 🔔 Notification System for Shared Tasks
- 📊 Admin Analytics Dashboard
  - Task status breakdown
  - Weekly & Monthly trends (using Chart.js)
- 🎨 Responsive UI using **TailwindCSS**

---

## 📂 Project Structure
```

Task\_Tracker/
│── Task\_Tracker/        # Main project folder
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
│── tasks/               # Application folder
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── serializers.py
│   ├── forms.py
│   └── ...
│
│── templates/           # HTML templates
│   ├── base.html
│   ├── tasks/
│   │   ├── dashboard.html
│   │   ├── login.html
│   │   ├── register.html
│   │   ├── form.html
│   │   └── tasklist.html
│
│── static/              # Static files
│   ├── css/form.css
│   └── js/app.js
│
│── manage.py

````

---

## ⚙️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/task-tracker.git
   cd task-tracker
````

2. **Create Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations**

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create Superuser (Admin)**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the Development Server**

   ```bash
   python manage.py runserver
   ```

7. Open in browser: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🔑<b> Default Credentials </b>

* Admin Dashboard: `/admin/`
* User Dashboard: `/dashboard/`

---

## 🛠️ <b>Tech Stack</b>

* **Backend**: Django 5, Django REST Framework
* **Frontend**: HTML, TailwindCSS, Chart.js
* **Database**: SQLite (default, can be replaced with PostgreSQL/MySQL)
* **Auth**: Django Authentication System

---

## 📊 Screenshots

### 🔐 Login Page
![Login Page](images/login.png)

### 📋 Task List
![Task List](images/Create_task.png)

### 📈 Analytics Dashboard
![Dashboard](images/dashboard.png)
---

## 📚 References

* [Django Official Docs](https://docs.djangoproject.com/en/5.1/)
* [Django REST Framework](https://www.django-rest-framework.org/)
* [Tailwind CSS](https://tailwindcss.com/docs)
* [Chart.js](https://www.chartjs.org/docs/latest/)

---

## 👨‍💻 Author

Developed by **Shankar Sable**
📅 June 2025

---

```
