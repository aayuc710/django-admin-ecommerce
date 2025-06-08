# 🛍️ Django E-Commerce Admin Panel

This is a Django-based admin dashboard project for managing an e-commerce platform. The admin panel allows administrators to manage products, categories, users, and orders in a secure and efficient way.

---

## 📌 Features

- Admin login and authentication
- Dashboard with order and product stats
- Product management (add, edit, delete)
- Category and subcategory management
- Order tracking and status updates
- User management
- Responsive design using Bootstrap
- Secure access for admins only

---

## 🛠️ Tech Stack

- **Backend**: Python, Django
- **Database**: SQLite / MySQL / PostgreSQL
- **Frontend**: HTML, CSS, Bootstrap
- **Authentication**: Django built-in auth system
- **Media Support**: Image upload for products

---

## ⚙️ Installation Steps

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/django-ecommerce-admin.git
cd django-ecommerce-admin
```
2. Create and activate a virtual environment
```bash
python -m venv env
source env/bin/activate        # Linux/Mac
env\Scripts\activate           # Windows
```
3. Install project dependencies
```bash
pip install -r requirements.txt
```
4. Set up the database
```bash
python manage.py makemigrations
python manage.py migrate
```
5. Create a superuser
```bash
python manage.py createsuperuser
```
6. Run the development server
```bash
python manage.py runserver
```
### 🌐 Environment Variables (optional)
Create a .env file (if you're using python-decouple or similar):

```env
SECRET_KEY=your_django_secret_key
DEBUG=True
DB_NAME=your_db_name
DB_USER=your_db_user
DB_PASSWORD=your_db_password
```
## 🧪 Running Tests
To run unit tests for the project:

```bash
python manage.py test
```
## 📂 Project Structure
php
ecommerce-admin/
├── ecommerce/            # Project configuration
├── dashboard/            # Main app with views, models, URLs
├── static/               # Static files (CSS, JS)
├── templates/            # HTML templates
├── media/                # Product image uploads
├── db.sqlite3            # Default database
├── manage.py
📸 Screenshots
Admin Login	Product Dashboard	Orders

## 🚀 Deployment Tips
Set DEBUG=False and add your domain to ALLOWED_HOSTS

Use gunicorn + Nginx for production

Set up static/media file serving in production

Can be deployed to Heroku, Render, or DigitalOcean

## 📬 Contact
Ayushi Patel
📧 patelaayushi1003@gmail.com
