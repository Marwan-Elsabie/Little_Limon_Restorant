# Little Lemon Restaurant 🍋

A Django-based website for the Little Lemon restaurant, featuring online menu browsing and table booking.

![Little Lemon Restaurant](static/img/mario-and-adrian.jpg)

## Features ✨

- **Menu System**: Browse food items with descriptions and prices
- **Online Booking**: Reserve tables through a form
- **Responsive Design**: Works on mobile and desktop
- **Modern UI**: Clean, Mediterranean-inspired styling
- **Admin Panel**: Manage menu and bookings (Django admin)

## Technologies Used 🛠️

- **Backend**: Django 4.1
- **Frontend**: HTML5, CSS3
- **Database**: SQLite (default)
- **Virtual Environment**: Pipenv
- **Deployment**: Ready for Heroku/Vercel (add `requirements.txt`)

## Installation Guide 📥

### Prerequisites
- Python 3.9+
- Pipenv (`pip install pipenv`)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/little-lemon.git
   cd little-lemon
2. Set up virtual environment and dependencies:
   pipenv install
   pipenv shell
3. Apply migrations:
   python manage.py migrate
4. Create superuser (optional):
   python manage.py createsuperuser
5. Run development server:
   python manage.py runserver

Project Structure 📂
littlelemon/
├── restaurant/               # Main app
│   ├── migrations/           # Database migrations
│   ├── templates/            # HTML templates
│   ├── __init__.py
│   ├── admin.py              # Admin configurations
│   ├── apps.py
│   ├── models.py             # Booking & Menu models
│   ├── tests.py
│   ├── urls.py               # App URLs
│   └── views.py              # View functions
├── static/                   # CSS, images, etc.
├── templates/                # Base templates
├── manage.py
└── Pipfile                   # Dependency management

Usage Examples 💻
*Access the website at http://localhost:8000

*Admin panel at http://localhost:8000/admin

*Menu page at http://localhost:8000/menu

*Booking page at http://localhost:8000/book

Screenshots 🖼️
Home Page	Menu Page
![image](https://github.com/user-attachments/assets/8cb54962-cf45-409c-a007-6a181b45b484)
![image](https://github.com/user-attachments/assets/798c580e-9c21-4785-84bc-4a180157c0d9)

Contributing 🤝
Contributions are welcome! Please fork the repository and create a pull request.

License 📄
This project is licensed under the MIT License - see the LICENSE file for details.
