
# Ticket Booking System

This is a Django-based Ticket Booking System. It allows users to register, log in, book tickets for different shows, and view their booking history. Admins can manage the shows and users through the Django admin panel.

## Features

- **User Authentication:**
  - Registration
  - Login/Logout
  - View booking history
- **Ticket Booking:**
  - Browse available shows
  - Book tickets
  - View booked tickets
- **Admin Panel:**
  - Manage users and shows
  - Administer bookings

## Technologies Used

- **Django**: Python web framework
- **SQLite**: Database (default for development)
- **Bootstrap 5**: Front-end framework for styling
- **Python 3.x**: Programming language

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repository-name.git
    ```
2. Navigate to the project directory:
    ```bash
    cd ticket_booking
    ```
3. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Apply migrations to set up the database:
    ```bash
    python manage.py migrate
    ```
5. Create a superuser to access the admin panel:
    ```bash
    python manage.py createsuperuser
    ```
6. Start the development server:
    ```bash
    python manage.py runserver
    ```
7. Visit `http://127.0.0.1:8000` in your browser to use the application.

## Directory Structure

```
ticket_booking/
│
├── booking/                      # The main app for booking functionality
│   ├── migrations/               # Database migrations
│   ├── templates/                # HTML templates
│   │   ├── user/                 # Templates related to user pages
│   │   │   └── booking_history.html
│   ├── views/                    # Views for handling requests
│   ├── models.py                 # Database models
│   └── urls.py                   # URL routing for the app
├── ticket_booking/               # Project settings
│   ├── settings.py               # Django settings
│   ├── urls.py                   # Project-wide URL routing
│   └── wsgi.py                   # WSGI entry point for deployment
├── manage.py                     # Django's command-line utility
└── requirements.txt              # Python package dependencies
```

# ScreenShot
### Home
![Screenshot 2025-04-25 190418](https://github.com/user-attachments/assets/d304a9fd-26c6-41be-8f77-1c847663d5ca)

### Login Pge
![Screenshot 2025-04-25 190728](https://github.com/user-attachments/assets/da088e0b-dadd-46cc-8d92-452151fce7ba)

### Book Tickit
![Screenshot 2025-04-25 190611](https://github.com/user-attachments/assets/7eb645ea-e88d-45ae-8052-c6fc16806a8b)

### Booking History Page
![Screenshot 2025-04-25 193647](https://github.com/user-attachments/assets/3df0213c-cf2f-4179-85d2-da1c8ddefd80)
