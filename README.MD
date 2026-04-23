# 🏨 Booking App

A full-stack hotel booking web application built with the MERN stack (MongoDB, Express, React, Node.js). Users can browse hotels, view room details, and make reservations.

---

## 🚀 Features

- 🔐 User authentication (Register / Login)
- 🏩 Browse and search hotels
- 🛏️ View room availability and details
- 📅 Make and manage reservations
- 👤 User profile management
- 🛠️ Admin panel to manage hotels and rooms

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- React Router

**Backend:**
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT Authentication

**DevOps:**
- Docker
- Docker Compose

---

## 📁 Project Structure

BookingApp/
├── api/                  # Backend (Node.js + Express)
│   ├── controllers/      # Route controllers
│   ├── models/           # Mongoose models
│   ├── routes/           # API routes
│   ├── utils/            # Helper functions
│   ├── index.js          # Entry point
│   └── Dockerfile
│
└── client/               # Frontend (React)
├── public/
├── src/
└── Dockerfile

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Docker](https://www.docker.com/) *(optional)*

### Installation

1. **Clone the repository**
```bash
   git clone https://github.com/momagdyy/Booking-App.git
   cd Booking-App
```

2. **Setup the API**
```bash
   cd api
   npm install
```

3. **Setup the Client**
```bash
   cd ../client
   npm install
```

4. **Configure environment variables**

   Create a `.env` file inside the `api/` folder:
```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=8800
```

### Running the App

**Backend:**
```bash
cd api
npm start
```

**Frontend:**
```bash
cd client
npm start
```

The app will be available at `http://localhost:3000`

---

## 🐳 Running with Docker

```bash
docker-compose up --build
```

---

## 📬 Contact

Made by [Mohamed Magdy](https://github.com/momagdyy)
