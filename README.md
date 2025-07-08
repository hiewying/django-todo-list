# Django Todo List

A simple To-Do application built with Django featuring user authentication (login/logout) and task management.

---

## Features

- User registration, login, and logout
- Create, update, delete, and view To-Do tasks
- Task ownership linked to authenticated users

---

## Usage

- Register a new account or log in with existing credentials.
- Add, edit, or delete your tasks.
- Log out securely when done.

---

## Screenshots



---

## Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/hiewying/django-todo-app.git
cd django-todo-app
```

2. **Create and activate a virtual environment**

```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
# Or
python -m pip install django
```

4. **Apply migrations**

```bash
python manage.py makemigrations
python manage.py migrate
```

5. **Create a superuser (optional, for admin access)**

```bash
python manage.py createsuperuser
```

6. **Run the development server**

```bash
python manage.py runserver
```

Visit http://127.0.0.1:8000 to see the app.




