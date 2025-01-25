# Django Project - Little Lemon Web Application

## Overview
This is the Django project for the **Little Lemon Web Application**, developed as part of the **Meta Backend Developer Certification Capstone Project**. This project implements a restaurant reservation and ordering system using Django, Django REST Framework, and PostgreSQL.

## Features
- **User Authentication**: Secure user authentication using Django's built-in authentication system.
- **Menu Management**: CRUD functionality for managing restaurant menu items.
- **Reservations**: Customers can book tables online.
- **Order Management**: Customers can place and track orders.
- **Admin Dashboard**: Django Admin for managing restaurant operations.
- **RESTful API**: API endpoints for frontend integration.

## Tech Stack
- **Backend**: Django, Django REST Framework (DRF)
- **Database**: PostgreSQL
- **Frontend**: React (planned for integration)
- **Containerization**: Docker (optional)

## Installation
### Prerequisites
- Python 3.10+
- PostgreSQL
- Docker & Docker Compose (optional but recommended)

### Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/little-lemon-web.git
   cd little-lemon-web
   ```

2. **Create and activate a virtual environment**
   ```sh
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   Create a `.env` file in the root directory and add the following:
   ```env
   SECRET_KEY=your_secret_key
   DEBUG=True
   DATABASE_URL=postgres://user:password@localhost:5432/little_lemon_db
   ```

5. **Apply migrations and create superuser**
   ```sh
   python manage.py migrate
   python manage.py createsuperuser
   ```

6. **Run the development server**
   ```sh
   python manage.py runserver
   ```

