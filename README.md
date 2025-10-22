# 🏠 StayBackend: The Airbnb Clone Project

StayBackend is a **backend system** inspired by Airbnb. It’s designed to handle property listings, bookings, user authentication, and reviews through a secure RESTful API.  
Built with **Django REST Framework** and **MySQL**, this project demonstrates real-world backend architecture, database design, and CI/CD integration.

---

## 🌍 Project Overview

The goal of StayBackend is to simulate the backend infrastructure of a platform like Airbnb — focusing on **data relationships**, **API security**, and **deployment workflows**.  
Users can:
- Register and log in (guest or host)
- Create and manage property listings
- Book stays and view reservations
- Leave reviews for listings

This project emphasizes scalability, maintainability, and security — essential traits of a production-grade application.

---

## 🧠 Learning Objectives

By completing this project, you will:
- Master **collaborative workflows** using Git and GitHub
- Understand **backend architecture** and **database design**
- Implement **secure authentication** using JWT
- Learn to build and test **RESTful APIs** with Django REST Framework
- Integrate **CI/CD pipelines** using GitHub Actions and Docker
- Strengthen skills in **documentation** and **project planning**

---

## ⚙️ Tech Stack

| Component | Technology |
|------------|-------------|
| **Backend Framework** | Django REST Framework |
| **Database** | MySQL |
| **Authentication** | JWT (JSON Web Tokens) |
| **CI/CD** | GitHub Actions + Docker |
| **Documentation** | Markdown |
| **Version Control** | Git & GitHub |

---

## 🧩 Core Features

### 👤 User Management
- Register, log in, and manage profiles
- Role-based access (guest or host)

### 🏠 Property Listings
- Hosts can create, update, and delete listings
- Guests can browse and view details
- Image upload support

### 📅 Bookings
- Guests can book available listings
- Hosts can view reservations for their properties
- Booking validation (no overlapping dates)

### ⭐ Reviews
- Guests can post reviews and ratings
- Listings display aggregated ratings

### 🔐 Security
- JWT-based authentication
- Input validation via serializers
- Rate limiting and CORS protection

---

## 🗃️ Database Design (MySQL)

**Entities and Relationships**

| Table | Description |
|--------|--------------|
| `users` | Stores user info (name, email, password, role) |
| `listings` | Property details (title, location, price, host_id) |
| `bookings` | Reservation info (listing_id, guest_id, check_in, check_out) |
| `reviews` | Ratings and comments for listings |
| `images` | URLs for listing photos |

**ERD Overview**

