# Flight Reservation

A simple desktop flight reservation GUI built with Python and Tkinter. Use it to search, book, edit, and delete flight reservations stored locally in a SQLite database.

## Key details discovered in the code
- Language: Python (files: Home.py, booking.py, reservation_list.py, database.py)
- GUI: tkinter (standard library)
- Calendar widget: tkcalendar (used in booking.py)
- Database: SQLite (flights.db, using Python's sqlite3 module)
- Entry point: Home.py (starts the Tkinter application)

## Features
- Book a flight (name, flight number, departure, destination, date, seat)
- View reservation list
- Edit and delete individual reservations
- Delete all reservations
- Local storage using a SQLite database file `flights.db`

## Tech stack
- Python 3.8+ (recommended)
- tkinter (GUI; usually included with Python but may need OS package)
- tkcalendar (pip package)
- sqlite3 (Python standard library; database file: `flights.db`)
