# Library Management System


## 📝 Project Description
E-Library Management System is a responsive web application developed for IMS566 Advanced Web Design Assignment. The system helps users manage book records and member information through a clean and user-friendly interface.

---

## ✨ Features Included
This prototype system comes equipped with several core features:
* **Secured Authentication Layout:** A responsive login page featuring strict credential validation.
* **Interactive Dashboard:** A clean admin panel layout integrated with live data visualization charts for book borrowing statistics.
* **Book Inventory (`data-1.html`):** A structured data table showcasing book availability statuses (*Available/Borrowed*).
* **Member Record (`data-2.html`):** A data table containing simulated registered library user profiles.
* **Responsive Layout:** Fully optimized for mobile, tablet, and desktop views utilizing the Bootstrap grid system.

---

## 🔐 Instructions to Test Login

* **Email:** `nurul@student.edu.my` 
* **Password:** `password123`

### Testing Steps:
1. Navigate to the main login page (`index.html`).
2. Input the exact email and password credentials provided above (the system will reject the login if any uppercase letters are used in the email).
3. Click the **Login** button.
4. If the credentials match, the system securely caches the session name via *Session Storage* and redirects you to the Dashboard with a personalized greeting (*"Welcome, Nurul!"*).
5. If incorrect, a red error alert box will dynamically appear.

---

## 🛠️ Frameworks & Libraries Used
This project integrates modern front-end libraries and tools to ensure optimal user experience:
1. **Bootstrap v5.3.3:** Used as the primary CSS framework for layout grids, card components, tables, and responsive utilities.
2. **Bootstrap Icons v1.13.1:** High-quality icon library utilized for navigational sidebars and interactive buttons.
3. **Chart.js:** A lightweight JavaScript library used to render the interactive bar charts on the dashboard.
4. **Vanta.js (Net Effect) & Three.js:** External animated script libraries utilized to generate the dynamic, interactive web/net background animation on the login screen.
5. **Google Fonts (Roboto):** The primary typography framework chosen to keep interface textual elements clean, clear, and professional.