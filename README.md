# Messo – Hostel Mess Management System

## Overview

Messo is a full-stack Hostel Mess Management System developed to simplify and digitize hostel mess operations. The system provides an efficient platform for students and administrators to manage menus, complaints, announcements, reviews, and other mess-related activities.

The application improves communication between students and mess administrators while reducing manual work and increasing transparency.

---

## Features

### User Authentication

* User Registration
* User Login
* JWT Authentication
* Secure Password Handling
* Protected Routes

### Mess Menu Management

* Daily Menu Display
* Meal Categorization
* Menu Updates by Administrators

### Complaint Management

* Submit Complaints
* Track Complaint Status
* Complaint Resolution System

### Announcement System

* Important Notices
* Event Announcements
* Real-Time Information Sharing

### Review and Feedback

* Student Feedback
* Ratings and Reviews
* Service Evaluation

### Admin Dashboard

* Manage Users
* Monitor Complaints
* Update Menus
* Post Announcements

---

## Tech Stack

### Frontend

* React.js
* React Router DOM
* Tailwind CSS
* Material UI

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JSON Web Token (JWT)

### Additional Tools

* Cloudinary
* Multer
* Axios

---

## System Architecture

```text
Frontend (React.js)
        ↓
REST API (Express.js)
        ↓
Authentication (JWT)
        ↓
MongoDB Database
```

---

## Project Structure

```text
Messo/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   └── mess-management/
│       ├── src/
│       ├── public/
│       ├── assets/
│       └── package.json
│
├── README.md
└── LICENSE
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/tarunre/Mess-management-system-in-Hostels.git
cd Mess-management-system-in-Hostels
```

### Backend Setup

```bash
cd backend
npm install
npm start
```

### Frontend Setup

```bash
cd frontend/mess-management
npm install
npm start
```

---

## Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Objectives

* Digitize hostel mess operations.
* Improve communication between students and management.
* Reduce paperwork.
* Provide transparency in complaint handling.
* Improve overall mess management efficiency.

---

## Advantages

* Easy to use interface.
* Secure authentication system.
* Efficient complaint handling.
* Centralized information management.
* Responsive design.
* Improved administrative efficiency.

---

## Future Enhancements

* Email Notifications
* SMS Alerts
* Online Payments
* Mobile Application
* Analytics Dashboard
* Real-Time Notifications

---

# Author

**Tarun Reddy**
B.Tech Student
Indian Institute of Information Technology and Management, Gwalior

---

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch.
5. Create a Pull Request.

---

## License

This project is licensed under the MIT License.

