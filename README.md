# Appointment Booking System

## Frontend

The frontend is built using **React** and **Node.js** (Node version **v25.1.0**) for building and running the application.

---

### How to Run the Frontend

1. Navigate to the root folder of the project:

   ```bash
   cd booking-system-ui

2. Install dependencies:
   ```bash
   npm install

3. Start the application:
   ```bash
   npm start

Landing Page

The landing screen is the Appointment Booking page where users can book an appointment will be available on http://localhost:3000
![landingPage.png](images/landingPage.png)

Admin Login

Admins can log in at: http://localhost:3000/login. A preloaded admin user is available for testing purposes: Username: sivejozi@gmail.com and
Password: test
![adminLogin.png](images/adminLogin.png)
Bookings Page

Once logged in, admins can view, update, and delete appointments on the bookings page: http://localhost:3000/bookings
![bookings.png](images/bookings.png)

On this page:

* Admins can edit an appointment directly in the grid popup editor.
* Admins can delete any appointment using the delete button.
* Both actions require the user to have the ROLE_ADMIN authority.
* These role-based access checks are enforced by the backend service.

Tech Stack Summary

* React 19
* DevExtreme DataGrid for appointment management UI
* JWT Authentication integrated with backend
* Fetch API for secured REST API communication
* Node.js v25.1.0 for local development and build environment
