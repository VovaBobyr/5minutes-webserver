# Project Created with AI within 5 minuntes :) including pushing to the git.

# Task Manager Web Application

A modern, beautiful task management web application built with Python Django. Keep track of your tasks with priority levels, status tracking, and due dates.

## Features

- ✨ **User Authentication**: Secure registration and login system
- 📋 **Task Management**: Create, read, update, and delete tasks
- 🎨 **Priority Levels**: Organize tasks by Low, Medium, or High priority
- 📊 **Status Tracking**: Mark tasks as Pending, In Progress, or Completed
- 📅 **Due Dates**: Set deadlines for your tasks
- 🔍 **Filtering**: Filter tasks by status and priority
- 💻 **Modern UI**: Beautiful, responsive design with Bootstrap 5
- 🔐 **Secure**: User-specific task isolation with Django authentication

## Technology Stack

- **Backend**: Python 3.12 + Django 5.2.7
- **Frontend**: HTML5, CSS3, Bootstrap 5.3.0
- **Database**: SQLite (default)
- **Icons**: Bootstrap Icons

## Installation

1. **Clone the repository** (if you haven't already)
   ```bash
   cd WebApp
   ```

2. **Create a virtual environment** (if not already created)
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run database migrations**
   ```bash
   python manage.py migrate
   ```

6. **Create a superuser** (optional, for admin access)
   ```bash
   python manage.py createsuperuser
   ```

7. **Start the development server**
   ```bash
   python manage.py runserver
   ```

8. **Open your browser** and visit:
   ```
   http://127.0.0.1:8000/
   ```

## Usage

1. **Register a new account** at `/register` or login at `/login`
2. **Create tasks** by clicking "New Task"
3. **View all tasks** on the home page
4. **Filter tasks** by status or priority using the filter controls
5. **Edit or delete tasks** using the action buttons
6. **View task details** by clicking on any task

## Project Structure

```
WebApp/
├── manage.py                 # Django management script
├── requirements.txt          # Python dependencies
├── README.md                # This file
├── taskmanager/             # Main project directory
│   ├── settings.py          # Django settings
│   ├── urls.py              # Main URL configuration
│   └── wsgi.py              # WSGI configuration
├── tasks/                   # Tasks application
│   ├── models.py            # Task data model
│   ├── views.py             # View functions
│   ├── forms.py             # Form definitions
│   ├── urls.py              # App URL routing
│   ├── admin.py             # Admin configuration
│   └── templates/           # HTML templates
│       ├── base.html        # Base template
│       └── tasks/           # Task-specific templates
├── venv/                    # Virtual environment
└── db.sqlite3               # SQLite database (created after migrate)
```

## Django Admin

Access the admin panel at `http://127.0.0.1:8000/admin/` using your superuser credentials.

## Development

To run the development server with auto-reload:
```bash
python manage.py runserver
```

To create new migrations after model changes:
```bash
python manage.py makemigrations
python manage.py migrate
```

## Screenshots

The application features:
- Gradient background with modern card-based UI
- Intuitive navigation and user-friendly interface
- Color-coded priority badges (green=low, orange=medium, red=high)
- Responsive design for mobile and desktop
- Beautiful Bootstrap Icons throughout

## License

This project is open source and available for personal and educational use.

## Author

Created with Django by your development team.

