# 🚆 Railway Reservation System

[![Live Demo](https://img.shields.io/badge/Demo-Live_Website-success?style=for-the-badge)](https://Captainkk620.github.io/Railway-Reservation-System/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)]()
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]()

A complete, interactive Single Page Application (SPA) for a Railway Ticket Booking System. Built as a college project to demonstrate modern frontend web development, dynamic DOM manipulation, and browser-based data storage.

**🌐 Live Website:** [Click here to view the live project](https://Captainkk620.github.io/Railway-Reservation-System/)

---

## 🌟 Key Features

### 👤 User Module
* **Dynamic Train Search:** Search for trains based on Source and Destination cities.
* **Real-Time Seat Availability:** View current seat counts which update automatically upon booking.
* **Ticket Reservation:** Input passenger details and book tickets with a single click.
* **Auto-PNR Generation:** System automatically generates a unique 10-digit PNR for every successful booking.
* **My Bookings Dashboard:** Users can view their complete booking history and ticket status.

### 🛡️ Admin Module
* **Admin Dashboard:** A dedicated view for administrators to monitor the railway network.
* **Train Management View:** See all active trains, routes, current capacities, and base fares.

### 💾 Database Simulation (Web Storage)
* **Persistent Storage:** Uses the HTML5 `localStorage` API. 
* **Data Retention:** Bookings and seat deductions remain saved even if the browser is closed or the page is refreshed, mimicking a real backend database.

---

## 💻 Technologies & Requirements

**Technologies Used:**
* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6)
* **Database:** Browser LocalStorage (NoSQL Document Store logic)
* **Architecture:** Single Page Application (SPA)

**System Requirements:**
* Any modern web browser (Google Chrome, Firefox, Microsoft Edge, or Safari).
* No local server (like Node.js or XAMPP) is required.

---

## 🚀 How to Run the Project

### Method 1: View Online (Recommended)
Simply click the live link hosted via GitHub Pages:  
👉 **[https://Captainkk620.github.io/Railway-Reservation-System/](https://Captainkk620.github.io/Railway-Reservation-System/)**

### Method 2: Run Locally on Your Computer
1. Download the `index.html` file from this repository.
2. Navigate to the folder where the file is downloaded.
3. Double-click `index.html` to open it in your default web browser.
4. The application will run immediately without any installation.

---

## 📁 Project Layout & Architecture

Since this project is optimized as a lightweight **Single-File SPA**, the architecture is divided into three distinct logical blocks within the `index.html` file:

```text
Railway-Reservation-System/
│
└── index.html
    ├── <style> Section          # CSS for modern cards, tables, navbars, and responsive design
    ├── <body> Section           # HTML UI Containers (Home, Search, Booking, Admin views)
    └── <script> Section         # JavaScript Logic
        ├── Data Models          # Train arrays and Booking objects
        ├── Storage Controllers  # localStorage get/set functions (Database)
        ├── UI Controllers       # DOM manipulation for navigating between pages
        └── Business Logic       # Search filtering, seat deduction, and PNR math
