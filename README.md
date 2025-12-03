# Hospital Management System

**Built with:** Python, Tkinter (GUI), SQLite (HospitalDB.db)

A lightweight desktop Hospital Management System that helps manage patients, appointments, employees, rooms and billing using a simple Tkinter GUI and a SQLite database. The project is structured as single-file forms for different modules (appointment_form.py, billing_form.py, employee_form.py, patient_form.py, room_form.py) with a `menu.py` launcher and `login.py` for authentication.

---

## Key Features

* Patient registration and management
* Employee (doctor/staff) management
* Create and manage appointments
* Room allocation and room management
* Billing and invoice generation
* Simple login/authentication
* Local persistence using SQLite (`HospitalDB.db`)

---

## Project Structure

```
HospitalDB.db        # SQLite database file
README.md
login.py             # Login / authentication window
menu.py              # Main menu / launcher
appointment_form.py  # Appointment creation & history
billing_form.py      # Billing and invoice handling
employee_form.py     # Employee CRUD operations
patient_form.py      # Patient CRUD operations
room_form.py         # Room allocation and management
```

---

## Prerequisites

* Python 3.8+
* Tkinter 
* SQLite3 

