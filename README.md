# Auditorium Seat Booking Application

## Overview
The Auditorium Seat Booking Application is a user-friendly and efficient solution for managing auditorium bookings, ensuring a seamless experience for both administrators and users.

## Features
- **User Registration and Login**: Allows users to create an account and log in securely.
- **Search and Filter**: Users can search for available seats based on date, time, and type of event.
- **Booking Management**: Users can view, modify, or cancel their bookings.
- **Admin Dashboard**: Comprehensive tools for administrators to manage bookings, view statistics, and handle user queries.
- **Payment Integration**: Secure payment processing for booking confirmations.

## Architecture
The application follows a modular architecture:
- **Frontend**: Developed using ReactJS for a dynamic and responsive user interface.
- **Backend**: Built with Node.js and Express, handling API requests and authentication.
- **Database**: MongoDB for storing user data, bookings, and auditorium configurations.

## Data Structure
The main data structures involved in this application include:
- **User**: Information such as name, email, password (hashed), and role (admin/user).
- **Booking**: Contains user ID, seat details, event ID, and booking status.
- **Event**: Includes event name, date, time, and auditorium details.

## Workflow
1. Users register and log in.
2. Users search for events and choose available seats.
3. Bookings are created, processed, and confirmed.
4. Users receive notifications regarding their booking status.
5. Administrators can manage events and bookings from the admin dashboard.

## Deployment Instructions
1. Clone the repository: `git clone https://github.com/s9182731/FGHS-Auditorium-Management.git`
2. Install dependencies:
   - For the backend: `npm install`
   - For the frontend: `cd client && npm install`
3. Set up environment variables for database connection and payment gateway.
4. Start the server: `npm start` for the backend.
5. Navigate to the client directory and run `npm start` to launch the frontend.
6. Access the application at `http://localhost:3000`.

## Conclusion
The Auditorium Seat Booking Application aims to provide a robust solution for managing auditorium bookings with a focus on user experience and administrative efficiency.
