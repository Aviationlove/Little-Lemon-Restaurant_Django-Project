# Little Lemon Restaurant - Django Project

## Description
Little Lemon is a restaurant reservation and menu management web application built with Django. It allows users to view the restaurant menu, make bookings, and manage reservations. The project demonstrates Django's core features, including models, views, forms, templates, and REST API integration.

## Features
- View restaurant menu items
- Make and manage table bookings
- View all bookings (admin)
- REST API authentication (Token & Session)
- User registration and authentication (via Djoser)
- Admin interface for menu and booking management

## Tech Stack
- Python 3
- Django 4.1+
- Django REST Framework
- Djoser (for authentication)
- MySQL (as the database backend)

## Instructions to Run Locally

1. **Clone the repository**
   ```
   git clone https://github.com/Aviationlove/Little-Lemon-Restaurant_Django-Project.git
   cd littlelemon
   ```

2. **Activate the virtual environment**
   ```
   # On Windows (PowerShell)
   Scripts/Activate
   ```

3. **Install dependencies**
   ```
   pip install django djangorestframework djoser mysqlclient
   ```

4. **Configure the database**
   - Ensure MySQL is running and a database named `reservations` exists.
   - Update the credentials in `littlelemon/settings.py` if needed.

5. **Apply migrations**
   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

6. **Create a superuser (for admin access)**
   ```
   python manage.py createsuperuser
   ```

7. **Run the development server**
   ```
   python manage.py runserver
   ```

8. **Access the application**
   - Main site: http://127.0.0.1:8000/
   - Admin: http://127.0.0.1:8000/admin/

## Website Screenshots

Add screenshots of your website below:

![Homepage Screenshot](static/Screenshot%202025-09-15%20225615.png)
![Booking Page Screenshot](static/Screenshot%202025-09-15%20225704.png)

## Project Structure
- `restaurant/` - Main app with models, views, forms, templates
- `littlelemon/` - Project settings and configuration
- `static/` - Static files (CSS, JS, images)

---

Feel free to customize the project for your own restaurant or learning purposes!
