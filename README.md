# HomelyHub – Smart Property Rental Platform

**HomelyHub** is a full-stack web application designed to simplify the process of renting and managing properties. It provides users with seamless login, property listing, image uploads, and booking functionalities — all powered by **MERN Stack (MongoDB, Express, React, Node.js)** and **ImageKit.io** for media management. ([GitHub][1])

---

## 🚀 Features

### ✔ User Module

* Register and log in securely (JWT-based authentication) ([GitHub][1])
* Manage personal profile
* View and manage bookings

### ✔ Property Module

* Add and manage property listings with detailed information
* Upload property images using ImageKit.io
* Filter properties by location, price, and amenities

### ✔ Booking & Payments

* View property details and availability
* Book accommodations with date-based options
* Integrated booking management dashboard

### ✔ Admin / Owner Side

* Create and edit property listings
* View all user bookings

---

## 🛠️ Tech Stack

| Layer          | Technology                                       |               |
| -------------- | ------------------------------------------------ | ------------- |
| Frontend       | React.js + Vite + Tailwind CSS                   |               |
| Backend        | Node.js + Express                                |               |
| Database       | MongoDB Atlas                                    |               |
| Media Storage  | ImageKit.io                                      |               |
| Authentication | JWT & Cookies                                    |               |
| Hosting        | Vercel (Frontend), Render or Localhost (Backend) | ([GitHub][1]) |

---

## 📁 Folder Structure

```
homelyhub-main/
├── frontend/     # React frontend (Vite)
│   ├── src/
│   └── package.json
├── backend/      # Node.js backend (Express)
│   ├── src/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── controllers/
│   │   └── utils/
│   └── package.json
└── .gitignore
```

([GitHub][1])

---

## 🔑 Environment Variables

Create a `.env` file in your `/backend` folder and include:

```
## Server
PORT=5000
NODE_ENV=development
CLIENT_URL=http://localhost:5173

## MongoDB
MONGO_URI=your_mongodb_connection_string

## JWT
JWT_SECRET=your_secret_key

## ImageKit
IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_URL_ENDPOINT=https://ik.imagekit.io/your_imagekit_id/
```

([GitHub][1])

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/abidraza-17/homelyhub.git
cd homelyhub-main
```

([GitHub][1])

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
npm start
```

Your backend should run at: `http://localhost:5000` ([GitHub][1])

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at: `http://localhost:5173` ([GitHub][1])

---

## 🛠 How It Works

1. User signs up / logs in (JWT-based authentication)
2. User browses available rental properties
3. Property owners add new listings with images via ImageKit
4. Users can book and view property details
5. Bookings are stored and retrievable via MongoDB Atlas ([GitHub][1])

---

## 📌 Deployment (Optional)

* **Frontend:** Deploy to Vercel
* **Backend:** Deploy to Render or Railway
* **Database:** MongoDB Atlas ([GitHub][1])

---

## 👩‍💻 Author

**Abinaya N**

* Email: `abinayaqw031@hmail.com`
* LinkedIn: [https://www.linkedin.com/in/abinaya-n-b06954375](https://www.linkedin.com/in/abinaya-n-b06954375) ([GitHub][1])

---

## 📄 License

This project is licensed under the **MIT License** — free to use and modify. ([GitHub][1])
