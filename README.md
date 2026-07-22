# Django Web Application with CI/CD

A simple Django web application developed using Python and Django, integrated with GitHub Actions for Continuous Integration (CI). The project demonstrates the use of Git, GitHub, Linux-based development, and automated workflow execution for validating the application on every code push.

---

## Features

- Django web application built using Python
- Follows Django's MVT (Model-View-Template) architecture
- URL routing and project configuration
- Git version control with GitHub
- Automated CI pipeline using GitHub Actions
- Automatic dependency installation
- Django project validation using `manage.py check`
- Linux-based development workflow

---

## Tech Stack

- Python 3.x
- Django
- Git
- GitHub
- GitHub Actions
- Linux

---

## Project Structure

```
test_django/
│
├── .github/
│   └── workflows/
│       └── django.yml
│
├── test_django_pro/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   ├── wsgi.py
│   └── __init__.py
│
├── manage.py
├── requirements.txt
└── README.md
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/ridhindas/test_django.git
```

```bash
cd test_django
```

### Create a virtual environment

Linux/macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

Windows

```cmd
python -m venv venv
venv\Scripts\activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the development server

```bash
python manage.py migrate
```

```bash
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/
```

---

## Running Project Validation

```bash
python manage.py check
```

---

## Continuous Integration

This project uses **GitHub Actions** to automate Continuous Integration.

The workflow performs the following tasks:

- Checks out the repository
- Sets up Python
- Installs project dependencies
- Runs Django project validation
- Ensures the application builds successfully on every push

---

## Skills Demonstrated

- Python Programming
- Django Framework
- Git & GitHub
- GitHub Actions
- Continuous Integration (CI)
- Linux
- Version Control
- Automation

---

## Future Enhancements

- Add Django applications
- Integrate PostgreSQL
- Dockerize the application
- Deploy on AWS EC2
- Configure Gunicorn and Nginx
- Implement Continuous Deployment (CD)

---

## Author

**Ridhin Das**

GitHub: https://github.com/ridhindas
