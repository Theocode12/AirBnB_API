# 🏡 Airbnb Clone

## 📌 Introduction
This project is a **Flask-based clone of Airbnb**, designed to replicate core functionalities such as property listings, user authentication, booking management, and reviews. Built with **Flask, MySQL, and Jinja templates**, this project demonstrates a **full-stack web application** with a dynamic frontend and a powerful backend.

## 🚀 Features

### 🔐 User Authentication
- Secure user login and session management
- User registration with profile management

### 🏠 Property Listings
- Users can **list** properties with images, descriptions, and prices
- View and filter properties based on various criteria

### 📅 Booking System
- Users can book available properties
- Reservation management with booking history

### ⭐ Reviews & Ratings
- Users can leave **reviews** and **ratings** for properties
- Review moderation to ensure quality feedback

### 🔍 Search & Filters
- Dynamic search for properties based on location, price, and availability
- Sorting by rating, price, and popularity

### 📡 RESTful API Endpoints
- Provides endpoints for listing properties, booking, and user authentication
- JSON responses for seamless frontend-backend integration

## 🛠️ Tech Stack
- **Backend:** Flask (Python)
- **Database:** MySQL
- **Frontend:** Jinja Templates, HTML/CSS, JavaScript
- **Authentication:** Flask-Login
- **Deployment:** Docker *(if applicable)*

## 🎯 Installation & Setup

### 1️⃣ Clone the Repository
```bash
$ git clone https://github.com/Theocode12/AirBnB_API.git
$ cd AirBnB_API
```

### 2️⃣ Set Up a Virtual Environment
```bash
$ python -m venv venv
$ source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
$ pip install -r requirements.txt
```

### 4️⃣ Set Up the Database
```bash
$ mysql -u root -p  # Log into MySQL
mysql> CREATE DATABASE airbnb_clone;
mysql> exit;

$ flask db upgrade  # Run database migrations
```

### 5️⃣ Run the Application
```bash
$ flask run
```
The application should now be accessible at **http://127.0.0.1:5000**

## 🏗️ API Endpoints *(If applicable)*
| Method | Endpoint | Description |
|--------|------------|--------------------------|
| GET | `/properties` | Fetch all property listings |
| GET | `/properties/<id>` | Get details of a specific property |
| POST | `/bookings` | Create a new booking |
| POST | `/login` | Authenticate a user |
| POST | `/register` | Register a new user |

## 🤝 Contr
