

# 💈 Barber Reservation System

A full-stack Barber Reservation System built using **Java, Spring Boot, React.js, and MySQL**.
This application allows users to book appointments, manage schedules, and handle payments securely using a **microservices architecture**.

---

## 🚀 Features

* User authentication (JWT-based)
* Real-time appointment booking
* Conflict-free slot management
* Admin dashboard for managing barbers & bookings
* Secure payment integration (Stripe / Razorpay)
* Email notifications

---

## 🛠️ Tech Stack

### 🔙 Backend:

* Java
* Spring Boot
* Spring Security (JWT)
* Spring Cloud (Microservices)
* MySQL

### 🎨 Frontend:

* React.js
* Tailwind CSS
* HTML5, CSS3

### 🧰 Tools:

* Git & GitHub
* Postman
* IntelliJ IDEA
* VS Code

---

## 📁 Project Structure

```bash
backend/
├── booking
├── category
├── payment
├── notifications
├── user-service
├── gateway-server
├── eureka-server
├── salon
├── review
├── service-offering

frontend/
```

---

## 🏗️ Microservices Architecture

This project follows a **microservices-based architecture** using Spring Boot and Spring Cloud.

### 🔹 Services:

* **Booking Service** – Handles appointment booking
* **Category Service** – Manages service categories
* **User Service** – User authentication & management
* **Payment Service** – Handles payments (Stripe/Razorpay)
* **Notification Service** – Email/SMS notifications
* **Salon Service** – Salon management
* **Review Service** – User reviews and ratings

### 🔹 Infrastructure:

* **Eureka Server** – Service discovery
* **API Gateway** – Centralized routing

---

## ⚙️ Backend Setup

```bash
cd backend
```

### ▶️ Run Services

* Start **Eureka Server**
* Start **Gateway Server**
* Start all microservices (booking, user, payment, etc.)

---

## 🎨 Frontend Setup

```bash
cd frontend
npm install
npm start
```



## 🔐 Environment Variables

Create a `.env` file (DO NOT push to GitHub):

```env
# Database
DB_URL=your_database_url
DB_USERNAME=your_username
DB_PASSWORD=your_password

# JWT
JWT_SECRET=your_secret_key

# Email Configuration (SMTP)
MAIL_USERNAME=your_email@gmail.com
MAIL_PASSWORD=your_app_password

# Payment
STRIPE_SECRET_KEY=your_key
RAZORPAY_KEY=your_key
```

---

## 📌 Notes

* Make sure MySQL is running locally
* Configure application.yml properly
* Do not expose secrets in GitHub (use `.env`)

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Prince Singh**


