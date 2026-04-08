# 🎬 Movie Ticket Booking System

<div align="center">

![Movie Ticket Booking](https://img.shields.io/badge/Movie-Ticket%20Booking-red?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xOCAzdjJoLTJ2LTJINHY2SDJ2MmgydjJIMlY3aDJ2Mmg0VjdoOHYyaDJ2LTJIMTN2Mmg0VjNoLTN6bTAgMTR2Mmgyek0xOCAxNXYyaC0yek0xOCAxM3YyaC0yek0xOCAxMXYyaC0yek0xOCA5djJoLTJ6Ii8+PC9zdmc+)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![SQL](https://img.shields.io/badge/SQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://javascript.com/)

**A full-stack cinema seat booking system with real-time availability tracking.**

[🚀 Live Demo](https://movie-ticket-booking-system-1-pnyt.onrender.com) • [📹 Demo Video](#demo-video) • [⚙️ Installation](#installation) • [📖 Features](#features)

</div>

---

## 🌐 Live Demo

> 🔗 **[https://your-live-demo-link.com](https://your-live-demo-link.com)**
> *(Replace with your deployed URL — e.g., Vercel, Render, Railway)*

---

## 📹 Demo Video

> 🎥 **[Watch Demo on YouTube / Google Drive](#)**
> *(Replace with your actual demo video link)*

<!-- Alternatively, if hosted on GitHub, embed like this:
![Demo GIF](./assets/demo.gif)
-->

---

## 🧩 Problem Statement

Build a system for a cinema hall where each show has limited seats. Users can book and cancel tickets. If all seats are booked, new bookings must be blocked automatically.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🪑 **View Available Seats** | See real-time seat availability for any show |
| 🎟️ **Book Tickets** | Select and book multiple seats at once |
| ❌ **Cancel Booking** | Cancel existing bookings and free up seats |
| 🚫 **Overbooking Prevention** | Automatically blocks bookings when all 20 seats are full |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React.js |
| **Backend** | Node.js + Express |
| **Database** | SQL (MySQL / SQLite) |
| **Styling** | CSS |

---

## 📁 Project Structure

```
Movie-Ticket-Booking-System/
└── movie-booking/
    ├── client/          # React frontend
    │   ├── src/
    │   │   ├── components/
    │   │   └── App.js
    │   └── public/
    ├── server/          # Node.js backend
    │   ├── routes/
    │   ├── db/
    │   └── index.js
    └── README.md
```

---

## ⚙️ Installation

### Prerequisites

- Node.js (v16+)
- npm or yarn
- MySQL / SQLite

### 1. Clone the Repository

```bash
git clone https://github.com/yandamurividyasagar-dev/Movie-Ticket-Booking-System.git
cd Movie-Ticket-Booking-System/movie-booking
```

### 2. Install Backend Dependencies

```bash
cd server
npm install
```

### 3. Install Frontend Dependencies

```bash
cd ../client
npm install
```

### 4. Configure Database

Create a `.env` file in the `server/` directory:

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=movie_booking
PORT=5000
```

Run the SQL schema (if provided):

```bash
mysql -u root -p movie_booking < db/schema.sql
```

### 5. Start the Application

**Backend:**
```bash
cd server
npm start
```

**Frontend:**
```bash
cd client
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🔌 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/api/seats` | Get all seat availability |
| `POST` | `/api/book` | Book one or more seats |
| `DELETE` | `/api/cancel/:id` | Cancel a booking |

---

## ⚙️ Constraints

- **Total seats per show:** 20
- Overbooking is not allowed — bookings beyond seat limit are rejected
- Multiple seats can be booked in a single transaction

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

Made with ❤️ by [yandamurividyasagar-dev](https://github.com/yandamurividyasagar-dev)

⭐ Star this repo if you found it helpful!

</div>
