# Doctor-Appointment-System
Doctor Appointment System with admin, patient and doctor modules
# 🩺 Doctor Appointment System

A full-stack Doctor Appointment Booking Platform built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This system allows patients to book appointments with doctors, and provides roles for **Admins**, **Doctors**, and **Patients**.

---

## 🚀 Features

### 🧑‍💻 User (Patient)
- Register / Login
- View list of available doctors
- Book appointments based on available slots
- View and cancel appointments

### 🩺 Doctor
- Login with credentials
- Set and manage availability slots
- View upcoming patient appointments
- Accept or reject bookings

### 🛠️ Admin
- Login as Admin
- View and manage all users and doctors
- Ability to reject appointments
- View total appointments and statistics

---

## 🛠️ Tech Stack

| Tech        | Role                            |
|-------------|---------------------------------|
| **MongoDB** | Database                        |
| **Express** | Backend framework (Node.js)     |
| **React.js**| Frontend library                |
| **Node.js** | Server runtime                  |
| **Mongoose**| ODM for MongoDB                 |
| **JWT**     | Authentication (Token-based)    |
| **Multer**  | File uploads (Profile pictures) |
| **Axios**   | HTTP client                     |
| **TailwindCSS** | Frontend styling            |

## 🔐 Authentication & Authorization

- JWT is used for secure token-based authentication.
- Tokens are sent in headers for protected routes.
- Middleware handles user verification and role-based access.


