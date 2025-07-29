# Birthdays Project CS50

A simple Flask web app that stores and displays people's birthdays using a SQLite database.

## Project Structure

birthdays/
│
├── app.py # Main Flask application
├── birthdays.db # SQLite database
├── templates/
│ └── index.html # Frontend HTML (rendered via Flask)
├── static/ # Optional: CSS or JS files
├── venv/ # Python virtual environment (optional but recommended)
└── README.md # This file


## Features

- Add a name and birthday (month + day)
- Store birthdays in a SQLite database
- View all stored birthdays on the homepage

## Requirements

- Python 3.x
- Flask
- SQLite3

Install dependencies:
    
    pip install -r requirements.txt
If requirements.txt doesn't exist, you can install Flask manually:
    
    pip install flask

## How to Run

Clone the repository or download the files.
(Optional) Create and activate a virtual environment:

    python -m venv venv
    source venv/bin/activate  # macOS/Linux
    venv\Scripts\activate     # Windows

Run the Flask app:
    
    flask run

Open your browser and go to http://127.0.0.1:5000
