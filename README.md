# 📝 Django Blog Website

A simple but complete **blog website** built with Python Django.  
This project is designed as a real-world learning exercise, demonstrating:

✅ Full CRUD (Create, Read, Update, Delete) for blog posts  
✅ User authentication (login/logout)  
✅ Comment system with approval  
✅ Categories and tags  
✅ Beautiful, responsive Bootstrap UI  

---

## 🌟 Features

- User registration and login
- Create, edit, delete posts (only for logged-in users)
- Public comments on posts
- Categories and tags for easy filtering
- Clean and responsive Bootstrap design

---

## ⚙️ Tech Stack

- Python 3.12
- Django 5.2
- SQLite (default)
- Bootstrap 5

---

## 🚀 Setup Instructions


<!-- 1. Clone the repository: -->

```bash
git clone <YOUR_REPO_URL>

cd blogs


# Create and activate virtual environment:
python -m venv venv
# Mac/Linux
source venv/bin/activate
# Windows
venv\Scripts\activate

# Install dependencies:
pip install -r requirements.txt

python manage.py migrate

# Run The Server
python manage.py runserver

# ✨ Author
Faith Onyibe

# 📜 License
This project is for learning and portfolio use.