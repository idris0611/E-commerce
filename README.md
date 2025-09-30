# Django eCommerce Website

<div align="center">

[![GitHub Repo](https://img.shields.io/badge/GitHub-MyRepo-blue?style=plastic&logo=github)](https://github.com/idris0611/E-commerce)
[![Access Here](https://img.shields.io/badge/Access-Here-brightgreen?style=plastic)](http://127.0.0.1:8000/)

</div>

This is a full-featured eCommerce website built using **Django**, a high-level Python web framework. The project includes user authentication, product browsing, shopping cart, checkout process, payment integration, order management, and more. It is designed to be **user-friendly, responsive, and scalable**.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)


## Features

- **User Authentication:** Registration, login, password reset, and profile management.
- **Product Catalog:** Browse and search products with images and descriptions.
- **Shopping Cart:** Add, update, and remove items easily.
- **Checkout:** Smooth checkout flow with order summary and address management.
- **Payment Integration:** Razorpay integration for secure payments.
- **Order Management:** View past orders and their status.
- **Responsive Design:** Works across desktop and mobile devices.
- **Admin Panel:** Manage products, orders, and users through Django’s admin.

## Technologies Used

- **Django:** Backend framework in Python
- **HTML/CSS/JavaScript:** Frontend development
- **Bootstrap:** Responsive design framework
- **Razorpay API:** Payment gateway

## Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/idris0611/E-commerce.git
cd Django-eCommerce-Website
```

2. **(Optional) Create virtual environment**
```bash
python -m venv venv
```

3. **Activate virtual environment**
```powershell
.\venv\Scripts\Activate   # Windows PowerShell
# or
source venv/bin/activate   # macOS/Linux
```

4. **Install dependencies**
```bash
pip install -r requirements.txt
```

5. **Set up environment variables**
- Create `.env` in project root.
- Add:
```
SECRET_KEY=<your-secret-key>
DEBUG=True
```
- Generate SECRET_KEY:
```python
from django.core.management.utils import get_random_secret_key
get_random_secret_key()
```

6. **Apply database migrations**
```bash
python manage.py migrate
```

7. **Create superuser**
```bash
python manage.py createsuperuser
```

8. **Run server**
```bash
python manage.py runserver
```
- Open browser: `http://127.0.0.1:8000/`

## Usage

- **Admin Panel:** `http://127.0.0.1:8000/admin/`
- **Users:** Browse products, add to cart, checkout, make payments, and manage profiles.
