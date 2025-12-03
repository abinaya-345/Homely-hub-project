# 🏡 HomelyHub – Smart Property Rental Platform

HomelyHub is a full-stack web application designed to simplify the process of renting and managing properties.  
It provides users with seamless login, property listing, image uploads, and booking functionalities — all powered by **MERN Stack (MongoDB, Express, React, Node.js)** and **ImageKit** for media management.

---

## 🚀 Features

### 👤 User Module
- Register and log in securely (JWT-based authentication)
- Manage personal profile
- View and manage bookings

### 🏠 Property Module
- Add and manage property listings with detailed information
- Upload property images using **ImageKit.io**
- Filter properties by location, price, and amenities

### 💳 Booking & Payments
- View property details and availability
- Book accommodations with date-based options
- Integrated booking management dashboard

### 🖥️ Admin/Owner Side
- Create and edit property listings
- View bookings made by users

---

## ⚙️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React.js + Vite + Tailwind CSS |
| Backend | Node.js + Express.js |
| Database | MongoDB Atlas |
| Media Storage | ImageKit.io |
| Authentication | JWT & Cookies |
| Hosting | Vercel (Frontend), Render / Localhost (Backend) |

---

## 🧩 Folder Structure

homelyhub-main/
├── frontend/ # React frontend (Vite)
│ ├── src/
│ └── package.json
│
├── backend/ # Node.js backend (Express)
│ ├── src/
│ │ ├── models/
│ │ ├── routes/
│ │ ├── controllers/
│ │ └── utils/
│ └── package.json
│
└── README.md

yaml
Copy code

---

## 🔑 Environment Variables

Create a `.env` file in your `/backend` folder and include:

```env
# Server
PORT=5000
NODE_ENV=development
CLIENT_URL=http://localhost:5173

# MongoDB
MONGO_URI=your_mongodb_connection_string

# JWT
JWT_SECRET=your_secret_key

# ImageKit
IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_URL_ENDPOINT=https://ik.imagekit.io/your_imagekit_id/
🛠️ Setup & Installation
1️⃣ Clone the repository
bash
Copy code
git clone https://github.com/abidraza-17/homelyhub.git
cd homelyhub-main
2️⃣ Backend Setup
bash
Copy code
cd backend
npm install
npm start
Your backend should run at:
👉 http://localhost:5000

3️⃣ Frontend Setup
bash
Copy code
cd frontend
npm install
npm run dev
Frontend runs at:
👉 http://localhost:5173

🧠 How It Works
User signs up / logs in (JWT-based authentication)

User browses available rental properties

Property owners can add new listings with images via ImageKit

Users can book and view property details

Bookings are stored and retrievable via MongoDB Atlas

🌐 Deployment (Optional)
Frontend: Deploy to Vercel

Backend: Deploy to Render or Railway

Database: MongoDB Atlas

Media Storage: ImageKit.io

🧑‍💻 Author
Mohammad Abid Raza
📧 [abidrazaf3@gmail..com]
💼 linkedin.com/in/mohammadabidraza
🌍 github.com/abidraza-17

📝 License
This project is licensed under the MIT License — free to use and modify.

