# 🌍 Tour Booking & Management System

![React](https://img.shields.io/badge/React-17-blue)
![Node.js](https://img.shields.io/badge/Node.js-18-green)
![Express](https://img.shields.io/badge/Express-4.18-lightgrey)
![MongoDB](https://img.shields.io/badge/MongoDB-6.0-brightgreen)

Full-stack tour booking platform with a complete admin panel, 
user dashboard, OTP authentication, and multilingual support.

🔗 **Live Demo:** [batkentravels.netlify.app](https://batkentravels.netlify.app)

---

## Features

### User Side
- **Authentication** — Register, login, logout with OTP email verification (Resend API)
- **Tour Browsing** — Search and filter by destination, dates, category, popularity
- **Tour Details** — Image gallery, description, highlights, itinerary, price, ratings
- **Booking System** — Select dates, number of guests, book and manage trips
- **User Dashboard** — View, edit, and cancel bookings
- **Multilingual Alerts** — i18n support across the app
- **Fully Responsive** — Mobile (320px) through large screens (1440px+)

### Admin Panel
- **Tours** — Full CRUD: create, edit, delete, manage tour listings
- **Bookings** — View and manage all customer bookings
- **Users** — Manage registered users
- **Resources** — Full CRUD for:
  - Employees
  - Partners
  - Customers (photos + testimonials/comments)
- **Analytics** — Stats and insights dashboard

---

## Tech Stack

**Frontend:** React.js · React Router · Axios · Cloudinary · Plain CSS

**Backend:** Node.js · Express · MongoDB · Mongoose · Resend API · Cloudinary SDK

---

## Architecture

```
tour-booking-app/
│
├── frontEnd/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── context/          # AuthContext
│       ├── api/              # axiosInstance
│       └── styles/
│
└── server/
    ├── controllers/
    ├── middleware/
    ├── models/
    ├── routes/
    └── utils/
          ├── cloudinary.js
          ├── sendOtp.js
          └── validateEmailDomain.js
```

---

## Run Locally

```bash
# Clone repository
git clone https://github.com/zarifull/tour-booking-app.git

# Frontend
cd frontEnd
npm install
npm start

# Backend
cd ../server
npm install
npm run dev
```

---

## Deployments

77 commits · 39 production deployments via Render & Netlify
