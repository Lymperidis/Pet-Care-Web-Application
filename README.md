# 🐾 Pet-Care Web Application

**University of Crete — Department of Computer Science**
**Course:** HY-359 Web Programming (Winter Semester 2023–2024)
**Project Type:** Team Project (2 members)
**Instructor:** M. Mountantonakis

---

## 📘 Overview

**Pet-Care** is a full-stack web information system designed to connect pet owners with pet keepers for temporary pet hosting.
It enables users to register, manage profiles, book stays, communicate, and review each other through an intuitive web interface.

This project was developed as part of the **HY-359 Web Programming** course, focusing on both client- and server-side technologies (HTML, CSS, JavaScript, JSP, Servlets, REST APIs, AJAX).

---

## 📸 Screenshots

### Landing Page
![Pet-Care Landing Page](./screeshots/pet-care-1.png)

### Admin Login
![Pet-Care Admin Login](./screeshots/pet2.png)

## 🎯 Features

### 👤 Administrator

* Separate secure login.
* Manage users (view & delete).
* View system statistics via **Google Charts** (e.g., number of pets, total earnings, user distribution).

### 🐕 Pet Owner

* Register, edit profile, and add pet information.
* Search and view available keepers (filter by type, location, and availability).
* Send and manage booking requests.
* Chat with pet keepers.
* Submit reviews after completed bookings.

### 🐾 Pet Keeper

* Register and update hosting profile.
* Manage bookings (accept, reject, or mark as finished).
* View hosting statistics (total days, completed bookings).
* Chat with pet owners.
* Use **ChatGPT API integration** for pet-care advice.

### 🌐 Visitor

* View pet keepers and basic information without logging in.
* Access helpful links and external pet-care resources.

---

## ⚙️ Technologies & Tools

**Frontend:**

* HTML5, CSS3, JavaScript, AJAX
* JSP pages
* Google Maps API
* Google Charts API

**Backend:**

* Java Servlets
* RESTful APIs
* MySQL Database

**Other:**

* ChatGPT API integration
* JSON handling
* Apache Tomcat
* RapidAPI for distance and route calculations

---

## 🧱 Architecture

* Follows a **three-tier MVC architecture** (Client–Server–Database).
* Uses **AJAX** for asynchronous data transfer.
* Implements **RESTful endpoints** for database communication.
* Ensures modularity, data encapsulation, and security best practices.

---

## 🔐 Security

* User authentication with separate access control for each role.
* Input validation and server-side checks.
* Defensive programming practices to prevent unauthorized access.
* Avoids storage of real or sensitive data (all dataset entries are fictional).

---

## 🧩 APIs & Integrations

* **Google Maps API** — display and calculate distances.
* **Google Charts API** — visualize statistics for admin users.
* **ChatGPT API** — provide dynamic pet-care information for keepers.
* **Trueway Matrix API (RapidAPI)** — driving distance and time calculations.

---

## 🚀 Learning Outcomes

* Full-stack web development experience.
* REST and AJAX communication between client and server.
* Use of APIs for visualization and data retrieval.
* Design of a secure and extensible web architecture.
* Team collaboration and modular system design.

---

## 👥 Authors

* [Lymperidis Lymperis]

---

