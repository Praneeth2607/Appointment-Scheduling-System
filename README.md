# Appointment Scheduling System

A full stack appointment scheduling application designed for managing interactions between patients and doctors. The system supports registration, authentication, doctor discovery, calendar-based slot booking, and appointment management through a clean REST API and a React-based frontend.

## Overview

This project simulates a real-world clinic or hospital appointment workflow. Patients can register, search for doctors, view availability through a calendar interface, and book appointment slots. Doctors can manage their profiles and view scheduled appointments. The backend enforces authentication, validation, and scheduling rules, while the frontend provides a simple and intuitive user experience.

The application is structured to clearly separate frontend, backend, and database concerns, making it suitable for learning and demonstration of full stack development practices.

## Features

### Patient

* Patient registration and login
* Search and view available doctors
* Calendar-based appointment slot booking
* View booked appointments

### Doctor

* Doctor registration and login
* Doctor profile management
* View upcoming appointments

### System

* Role-based authentication using JWT
* RESTful API design
* Appointment and slot validation
* Centralized error handling

## Tech Stack

### Frontend

* React
* JavaScript, HTML, CSS
* Axios for API communication

### Backend

* Node.js
* Express.js
* MongoDB with Mongoose
* JSON Web Tokens for authentication

## Project Structure

```
appointment-scheduling-system-main/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middlewares/
│   ├── errors/
│   ├── db/
│   └── app.js
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── App.js
│       ├── index.js
│       └── styles
│
├── Screenshots/
│   ├── calendar.png
│   ├── search.png
│   └── slot_booking.png
│
└── README.md
```

## Setup Instructions

### Prerequisites

* Node.js
* MongoDB

### Backend Setup

1. Navigate to the backend directory
2. Install dependencies

   ```
   npm install
   ```
3. Configure environment variables

   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
4. Start the backend server

   ```
   npm start
   ```

### Frontend Setup

1. Navigate to the frontend directory
2. Install dependencies

   ```
   npm install
   ```
3. Start the frontend application

   ```
   npm start
   ```

## Screenshots

UI screenshots demonstrating registration, doctor search, calendar booking, and profile pages are available in the `Screenshots` folder.

## Learning Outcomes

* Designing REST APIs with Express
* Structuring MongoDB schemas with Mongoose
* Implementing authentication and middleware
* Managing full stack data flow
* Organizing scalable project architecture

## Future Enhancements

* Appointment reminders and notifications
* Admin dashboard for system oversight
* Improved calendar availability controls
* Enhanced UI and accessibility

## Author

Developed as a full stack appointment scheduling system for learning and demonstration purposes.

