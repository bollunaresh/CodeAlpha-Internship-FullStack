# 🌐 Social Media App (CodeAlpha Internship Task)

A simple **social media web application** built with Django.  
Features:
- User Registration / Login
- User Profiles
- Create Posts with Images
- Like / Unlike Posts
- Comment on Posts
- Feed Page

## ⚡ Setup Instructions
```bash
git clone https://github.com/your-username/CodeAlpha_SocialMedia_App.git
cd CodeAlpha_SocialMedia_App
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
Open → `http://127.0.0.1:8000/`
