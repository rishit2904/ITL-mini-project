# 💼 Job Application Portal

A Django-based web application for managing job postings and applications, featuring user authentication, job listings, and application tracking.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Django](https://img.shields.io/badge/Django-Framework-green.svg)
![SQLite](https://img.shields.io/badge/SQLite-Database-lightgrey.svg)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-Frontend-orange.svg)

## 📋 Overview

This project is a full-stack job application portal built with Django. It provides a platform for employers to post jobs and for job seekers to browse and apply for positions.

## ✨ Features

- **User Authentication**: Register, login, and manage user profiles
- **Job Listings**: Browse and search available job postings
- **Application System**: Apply for jobs with easy-to-use forms
- **Admin Dashboard**: Manage jobs, users, and applications
- **Responsive Design**: Works on desktop and mobile devices

## 📁 Project Structure

```
ITL-mini-project/
├── manage.py           # Django management script
├── db.sqlite3          # SQLite database
├── myproject/          # Project settings
├── myapp/              # Main application module
├── jobapp/             # Job application module
├── templates/          # HTML templates
└── static/             # CSS, JavaScript, images
```

## 🛠️ Tech Stack

- **Backend**: Python, Django
- **Database**: SQLite3
- **Frontend**: HTML5, CSS3, JavaScript
- **Template Engine**: Django Templates

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/rishit2904/ITL-mini-project.git
   cd ITL-mini-project
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install django
   ```

4. **Run migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create superuser** (for admin access)
   ```bash
   python manage.py createsuperuser
   ```

6. **Start the development server**
   ```bash
   python manage.py runserver
   ```

7. **Access the application**
   - Main Site: `http://127.0.0.1:8000/`
   - Admin Panel: `http://127.0.0.1:8000/admin/`

## 📱 Usage

### For Job Seekers
1. Register for an account
2. Browse available job listings
3. Apply for positions of interest
4. Track application status

### For Employers/Admin
1. Login to admin dashboard
2. Create and manage job postings
3. Review applications
4. Manage user accounts

## 🔧 Configuration

Key settings in `myproject/settings.py`:
- `DEBUG`: Set to `False` in production
- `SECRET_KEY`: Change in production environment
- `ALLOWED_HOSTS`: Add your domain when deploying

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **Star this repository if you found it helpful!**
