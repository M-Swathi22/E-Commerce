# 🛍️ e-website – E-commerce Website using Django

This is a full-featured e-commerce website built using Django, MySQL, HTML, CSS, Bootstrap, and JavaScript. It includes user authentication, product listing, cart, wishlist, order placement, and Stripe payment gateway.

---

## 🚀 Features

- 🧑‍💻 User Registration and Login
- 🗂️ Product Categories: Mobile, Electronics, Books, Fashion, Home, Grocery
- 📦 Product Listing with Details
- 🛒 Cart Functionality (Add, Remove, Quantity)
- ❤️ Wishlist Feature
- 📍 Address Collection at Checkout
- 📦 Order Confirmation & Placement
- 💳 Stripe Payment Integration
- 🔐 Secure Configuration (`settings_.py` for sensitive info)
- 📦 GitHub `.gitignore` for virtual env and DB credentials
- 📱 Mobile responsive design using Bootstrap

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** Python, Django
- **Database:** MySQL
- **Payment:** Stripe

---

E-Project/
│
├── django_site/
│   ├── ecommerce/              # Main Django project folder
│   │   ├── __init__.py
│   │   ├── asgi.py
│   │   ├── settings.py
│   │   ├── settings_secret.py  # Keep gitignored
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │
│   ├── crud_app/               # Main Django app
│   │   ├── migrations/
│   │   ├── static/             # Static files (CSS, JS, images)
│   │   ├── templates/          # HTML templates
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── models.py
│   │   ├── tests.py
│   │   ├── urls.py
│   │   ├── views.py
│   │
│   ├── manage.py               # Django management script
│   ├── README.md               # Project README
│   ├── .gitignore              # Git ignore file
│
├── envsite/                     # Virtual environment (optional to push)
│   ├── Lib/
│   ├── Scripts/
│   ├── pyvenv.cfg

### 🏠 Home Page
![Home Page](screenshots/home.png)

