# Hospital Management System

A Flask-based Hospital Management System for managing doctors, patients, bookings, and user authentication.

## Features

- Doctor and patient registration
- Patient appointment booking
- View and manage bookings
- Search doctor by department or name
- Login and signup system
- SQLite database support for local development

## Project Structure

```text
Hospital-Management-System-dbmsminiproject-main/
└── hospital system/
    └── PROJECT/
        ├── main.py
        ├── static/
        ├── templates/
        └── hms.db
```

## Requirements

Install dependencies using:

```bash
pip install Flask Flask-SQLAlchemy Flask-Login
```

## Run the Project

1. Open a terminal in the project folder.
2. Run:

```bash
python main.py
```

3. Open the app in your browser:

```text
http://127.0.0.1:5000/
```

## Default Database

This project uses SQLite by default so it works locally without MySQL setup.

## Notes

- The app is designed for learning/demo use.
- You can later switch the database configuration to MySQL by updating the SQLAlchemy connection string.

## Author

Arun Kumar
