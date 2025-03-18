# Supermarket-Booking-System-Python-
Supermarket Booking System
==========================

This is a Python-based Supermarket Booking System that allows users to manage booking slots in a supermarket. The system enables adding slots, booking slots, and displaying the current status of all slots.

Features
--------
- Add booking slots with defined time and capacity.
- Book slots with available capacity.
- Display all slots with their current booking status.
- Prevents overbooking beyond slot capacity.

How to Use
----------
1. Clone the repository or download the source code.
2. Run the program using a Python interpreter (Python 3.7+ recommended).
3. Interact with the system by adding slots, booking slots, and viewing slot statuses.

Sample Code Execution
---------------------
[{'time': '10:00 AM', 'capacity': 10, 'booked': 0}, {'time': '11:00 AM', 'capacity': 15, 'booked': 0}]
True
[{'time': '10:00 AM', 'capacity': 10, 'booked': 5}, {'time': '11:00 AM', 'capacity': 15, 'booked': 0}]
False
[{'time': '10:00 AM', 'capacity': 10, 'booked': 5}, {'time': '11:00 AM', 'capacity': 15, 'booked': 0}]

System Requirements
-------------------
- Python 3.7 or above
- Basic Python packages (No external libraries required)

Setup and Run
-------------
1. Install Python from the official Python website: https://www.python.org/
2. Save the Python script as `supermarket_booking.py`.
3. Open a terminal or command prompt and run:
   python supermarket_booking.py

