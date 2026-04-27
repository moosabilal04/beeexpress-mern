# BeeExpress

A full-stack web application that streamlines food ordering, table reservations, and event hall bookings — helping users avoid wait times and secure their desired spaces in advance.

> Final Year Project | COMSATS University Islamabad | 2022

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React.js |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Auth | JWT (JSON Web Tokens) |

---

## Features

- Food Ordering — Browse menus and place food orders online
- Table Reservations — Reserve tables in advance at restaurants
- Hall Bookings — Book event halls for occasions
- Authentication — Secure signup/login with JWT
- Role-Based Access — Separate dashboards for Admin, Manager, Customer and Delivery Boy
- Order Tracking — Real-time order and reservation management

---

## Project Structure

```
BeeExpress/
├── backend/         # Node.js + Express REST API
│   ├── models/      # MongoDB schemas
│   ├── routes/      # API endpoints
│   └── server.js    # Entry point
└── frontend/        # React.js client
    ├── src/
    │   ├── customer components/
    │   └── styles/
    └── public/
```

---

## Getting Started

### Prerequisites
- Node.js
- MongoDB

### Installation

```bash
# Clone the repo
git clone https://github.com/moosabilal04/beeexpress-mern.git
cd beeexpress-mern

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

### Running the App

```bash
# Start backend (from /backend)
npm start

# Start frontend (from /frontend)
npm start
```

---

## Environment Variables

Create a `.env` file inside the `/backend` folder and add:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

> Never commit your `.env` file to GitHub.

---

## Developer

**Moosa Bilal** — Full-Stack Developer
[GitHub](https://github.com/moosabilal04)
