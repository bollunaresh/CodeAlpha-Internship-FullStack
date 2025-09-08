# 🛒 Simple E-commerce Store (CodeAlpha Internship Task)

This is a **Simple E-commerce Web Application** built using **Django** for the backend and basic HTML/CSS for the frontend.  
It allows users to **view products, see product details, add items to cart, and place orders** after logging in.

---

## 🚀 Features
- User Registration & Login (Django Auth)
- Product Listings
- Product Details Page
- Shopping Cart
- Order Placement
- Admin Panel for managing products & orders
- Image upload for products

---

## 🛠️ Tech Stack
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS
- **Database**: SQLite (default)
- **Authentication**: Django Auth System

---

## ⚡ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/CodeAlpha_Ecommerce_Store.git
   cd CodeAlpha_Ecommerce_Store
   ```

2. Create & activate virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate  # Windows
   source venv/bin/activate  # Linux/Mac
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

5. Create superuser:
   ```bash
   python manage.py createsuperuser
   ```

6. Run development server:
   ```bash
   python manage.py runserver
   ```

7. Open in browser:
   ```
   http://127.0.0.1:8000/
   ```

---

## 📌 Internship Task Info
This project was developed as part of **CodeAlpha Full Stack Development Internship**.  
Task: **Simple E-commerce Store** using Django.
