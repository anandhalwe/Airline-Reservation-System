
# ✈️ Airline Reservation System

A web-based application built as a part of the Post Graduate Diploma in Advanced Computing (PG-DAC) course at C-DAC Hyderabad. The project provides a complete airline ticket booking solution for users, administrators, and vendors.

---

## 📌 Features

### 👤 User
- Register and login
- Search flights between source and destination
- Book, cancel, or view tickets
- Secure login with JWT-based authentication
- Forgot password with account lock feature after multiple failed attempts

### 🔧 Admin
- Login and manage system
- Add, edit, or cancel flights
- View customer bookings and feedback
- Block/unblock suspicious user accounts

### 🧑‍💼 Vendor
- Register flights
- Modify or remove flight details
- View booked flights
- Act as intermediary for booking confirmations

---

## 🛠️ Tech Stack

- **Frontend**: ReactJS, JavaScript, HTML, Bootstrap
- **Backend**: Java, Spring Boot (REST API, Spring Security with JWT)
- **Database**: MySQL
- **Development Tools**: IntelliJ IDEA, Visual Studio Code, Postman

---

## 🗄️ Database Design

- MySQL with tables for users, flights, bookings, and feedback
- Entity-Relationship (ER) model used for structured schema
- Data security and integrity ensured through backend validations

---

## 🔐 Authentication & Security

- JWT-based access and refresh tokens
- Secure login/logout flows
- Account lockout after 5 failed attempts
- Admin control over suspicious accounts

---

## 🧪 Testing

- Validated user registration, login, flight booking, and cancellation
- Admin and vendor modules tested for flight and user management
- Password recovery and security features verified

---

## ⚙️ Setup Instructions

Follow these steps to set up and run the project locally:

### 🔧 Backend Setup (Spring Boot + MySQL)

1. **Create a MySQL database**:
   ```sql
   CREATE DATABASE airline_reservation;
   ```

2. **Configure `application.properties`**:
   Open the `application.properties` file and update the following lines:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/<YOUR_DATABASE_NAME>
   spring.datasource.username=root
   spring.datasource.password=<YOUR_DATABASE_PASSWORD>
   ```

3. **Install dependencies**:
   - Maven/Gradle will download dependencies automatically in your IDE
   - Make sure **Lombok** is enabled in your IDE (IntelliJ IDEA/VS Code)

4. **Run the backend**:
   Run the main file:  
   ```java
   AirplaneServiceApplication.java
   ```

### 💻 Frontend Setup (ReactJS)

1. Navigate to the frontend project directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the React development server:
   ```bash
   npm start
   ```

4. The frontend should be live at:
   ```
   http://localhost:3000
   ```

---

## 🎯 Project Objective

The Airline Reservation System aims to automate the flight booking process, reduce manual errors, and provide a convenient interface for both airline staff and customers. It ensures fast, secure, and reliable ticketing while managing real-time flight data and user interactions.

---

## 📚 References

- [ReactJS Documentation](https://reactjs.org/docs/getting-started.html)
- [Spring Boot Reference](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
- [MDN JavaScript Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Oracle Java Docs](https://docs.oracle.com/en/java/)
- [MySQL Docs](https://dev.mysql.com/doc/)
- [Visual Studio Code Docs](https://code.visualstudio.com/docs/)

---

## 👨‍💻 Developed By

- Anand A. Halwe  
---

## 🙏 Thank You!
