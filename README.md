# Movie Ticket Booking System

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://javascript.com/)

A simple cinema seat booking app where users can view seats, book tickets, and cancel bookings. Built with React on the frontend and Node.js + SQLite on the backend.

🔗 **Live Demo:** https://movie-ticket-booking-system-1-pnyt.onrender.com

---

## Demo

https://github.com/user-attachments/assets/d563f602-e02f-4543-8d48-df47266c94a6

---

## What it does

- View all available seats for a show
- Book single or multiple seats at once
- Cancel an existing booking
- Blocks new bookings when all 20 seats are taken

---

## Tech Stack

- **Frontend** — React.js, CSS
- **Backend** — Node.js, Express
- **Database** — SQLite

---

## Project Structure

```
Movie-Ticket-Booking-System/
└── movie-booking/
    ├── frontend/        # React app
    └── backend/         # Express server + SQLite DB
```

---

## Getting Started

**Clone the repo**
```bash
git clone https://github.com/yandamurividyasagar-dev/Movie-Ticket-Booking-System.git
cd Movie-Ticket-Booking-System/movie-booking
```

**Run the backend**
```bash
cd backend
npm install
node server.js
```

**Run the frontend**
```bash
cd frontend
npm install
npm start
```

App runs on http://localhost:3000

---

## API

| Method | Endpoint | What it does |
|---|---|---|
| GET | `/api/seats` | Fetch all seats |
| POST | `/api/book` | Book seats |
| DELETE | `/api/cancel/:id` | Cancel a booking |

---

## Constraints

- Max 20 seats per show
- Can't book if show is full
- Multiple seats can be booked at once

---

Built by [yandamurividyasagar-dev](https://github.com/yandamurividyasagar-dev)
