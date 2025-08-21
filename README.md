# Django Starter Site

[![Django CI](https://github.com/sambit-04/django-starter-site/actions/workflows/django.yml/badge.svg)](https://github.com/sambit-04/django-starter-site/actions/workflows/django.yml)
[![codecov](https://codecov.io/gh/sambit-04/django-starter-site/branch/main/graph/badge.svg)](https://codecov.io/gh/sambit-04/django-starter-site)
[![Coverage Report](https://img.shields.io/badge/coverage-report-blue)](https://sambit-04.github.io/django-starter-site/coverage/)

A basic Django starter project with templates, static files, media handling, and an example app. Includes admin setup, home/about pages, and configured settings for static & media assets. Perfect as a boilerplate for learning Django or kickstarting new web projects.

---

## ⚡ Features
- Django project with **templates**, **static files**, and **media handling**
- Ready-to-use **views** and **URL routing**
- **Admin panel** enabled with superuser setup
- **Static + Media configuration** in `settings.py`
- CI/CD with **GitHub Actions**
- **Test coverage reports** published on GitHub Pages

---

## 🛠️ Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/django-starter-site.git
   cd django-starter-site
   ```
   
2. Create a virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate   # On Windows
   source venv/bin/activate  # On Linux/Mac
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. Create superuser:
   ```bash
   python manage.py createsuperuser
   ```

6. Start development server:
   ```bash
   python manage.py runserver 8080
   ```

7. Open in browser:

   `http://127.0.0.1:8000/`

---

## 📊 Coverage & Reports
- Live Coverage Badge: [![codecov](https://codecov.io/gh/sambit-04/django-starter-site/branch/main/graph/badge.svg)](https://codecov.io/gh/sambit-04/django-starter-site)
- Full Coverage Report: [View Here](https://sambit-04.github.io/django-starter-site/coverage/)
📊 To view detailed test coverage, download the **coverage-report artefact** from your GitHub Actions run and open `index.html` inside `htmlcov/` in your browser.


---

## 🤝 Contributing
Pull requests are welcome!  
For major changes, open an issue first to discuss what you’d like to change.

---

## 📜 License
This project is licensed under the **MIT License**.
