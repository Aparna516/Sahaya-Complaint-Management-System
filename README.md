# SAHAYA: Smart Grievance Management System

SAHAYA is a web-based portal designed to bridge the gap between citizens and the government. It uses intelligent keyword logic to automatically route public complaints to the correct departments.

## 📋 Requirements
* **Language:** Python 3.10+
* **Framework:** Flask
* **Database:** SQLite (SQLAlchemy ORM)
* **Email:** SMTP Service for real-time alerts

## 🚀 How to Run
1. Install dependencies:
   `pip install -r requirements.txt`
2. Run the application:
   `python app.py`
3. Access the portal at `http://127.0.0.1:5000/`

## ✨ Features
* **Automated Routing:** Complaints are categorized into Health, Roads, Electricity, etc.
* **Admin Dashboard:** Officers can update status from 'Pending' to 'Resolved'.
* **Secure Hashing:** All passwords are encrypted using Werkzeug.
