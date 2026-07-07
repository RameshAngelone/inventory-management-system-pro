# Inventory Management System Pro v1.0

A professional cloud-based Inventory Management System built using **HTML5**, **CSS3**, **Bootstrap 5**, **Vanilla JavaScript**, **Google Apps Script**, and **Google Sheets**.

The application is hosted on **Vercel**, while the backend is powered by **Google Apps Script REST APIs** with **Google Spreadsheet** acting as the database.

---

# Project Information

**Project Name**

Inventory Management System Pro v1.0

**Repository**

inventory-management-system-pro

**Version**

v1.0

---

# Technology Stack

## Frontend

* HTML5
* CSS3
* JavaScript (ES6+)
* Bootstrap 5
* Font Awesome

## Backend

* Google Apps Script
* REST JSON API

## Database

* Google Spreadsheet

Spreadsheet Name

Tile Planet Live Inventory

User Sheet

USERS

## Source Control

GitHub

## Hosting

Vercel

---

# System Architecture

```
Browser
    │
    ▼
Vercel Hosted Frontend
    │
    ▼
JavaScript Fetch API
    │
    ▼
Google Apps Script REST API
    │
    ▼
Google Spreadsheet
```

---

# Development Principles

* Commercial-grade architecture
* Production-ready code only
* Modular design
* One file at a time
* No placeholder code
* No demo code
* Clean and maintainable source code
* Responsive user interface
* Secure authentication
* JSON-based API communication
* Separation of frontend and backend
* Version-controlled development through GitHub

---

# Current Development Phase

## Phase 1 – Authentication

Modules included:

* Login
* Create Account
* Edit Account
* Delete Account

No inventory features will be developed until the authentication system is fully completed and tested.

---

# Database (USERS Sheet)

| Column | Field         |
| ------ | ------------- |
| A      | UserID        |
| B      | Username      |
| C      | Password_Hash |
| D      | Full_Name     |
| E      | Mobile        |
| F      | Email         |
| G      | Role          |
| H      | Dealer_ID     |
| I      | Status        |
| J      | Approved      |
| K      | Approved_By   |
| L      | Approved_At   |
| M      | Last_Login    |
| N      | Created_At    |
| O      | Updated_At    |

---

# Authentication Rules

* Usernames must be unique.
* Passwords are never stored in plain text.
* Authentication uses password hashing.
* Only approved users can log in.
* Only active users can access the application.
* Every successful login updates the Last_Login timestamp.

---

# Future Development Roadmap

## Phase 2

* Product Search
* Live Inventory
* Stock Availability
* Product Details

## Phase 3

* Sales
* Purchase
* Dealers
* Customers
* Reports

## Phase 4

* Dashboard
* Analytics
* Stock Movement
* Notifications
* Advanced Reports

---

# Project Structure

```
inventory-management-system-pro/

├── frontend/
├── backend/
├── docs/
├── README.md
├── .gitignore
└── LICENSE
```

---

# Coding Standards

* One file per development step
* Every file reviewed before moving forward
* Meaningful naming conventions
* Modular functions
* Consistent code formatting
* Production-quality implementation
* No unnecessary dependencies

---

# License

This project is proprietary and intended for commercial use unless otherwise specified.
