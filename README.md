# 🛕 Pujanam – Pandit Booking & Puja Services Platform

<p align="center">
  A Full Stack MERN Application for Online Puja Services and Pandit Booking
</p>

<p align="center">
  <a href="https://pujanam.netlify.app/">
    <img src="https://img.shields.io/badge/Live_Demo-Visit_Pujanam-2ea44f?style=for-the-badge" alt="Live Demo"/>
  </a>
  <img src="https://img.shields.io/badge/React.js-Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
</p>

---

## 📌 Overview

**Pujanam** is a full-stack web application designed to simplify the process of discovering puja services and booking verified pandits online.

The platform provides a centralized system where users can browse puja services, book pandits, and manage their bookings. It offers dedicated dashboards for Users, Pandits, and Admins with role-based access control and efficient management capabilities.

The application is built using the MERN stack, providing a responsive user experience and a scalable backend architecture.

🔗 **Live Application:** https://pujanam.netlify.app/

---

## ✨ Key Features

- 🔐 **Authentication & Authorization:** JWT-based authentication with role-based access control.
- 👤 **Multiple User Roles:** Dedicated functionality for Users, Pandits, and Admins.
- 🛕 **Puja Services:** Browse and explore available puja services.
- 📅 **Pandit Booking:** Book verified pandits for different puja requirements.
- 📋 **Booking Management:** Manage and track booking information.
- ⚙️ **Service Management:** Manage puja service details.
- 🧑‍💼 **Profile Management:** Dedicated profile management for users and pandits.
- ☁️ **Image Management:** Cloudinary integration for image uploads and storage.
- 📱 **Responsive Design:** Mobile-friendly interface built with React.js and Tailwind CSS.

---

## 🖥️ Application Screenshots

> Add your actual application screenshots in the `screenshots` directory.

### Home Page

# ![Pujanam Home Page](screenshots/home.png)

### User Dashboard

# ![User Dashboard](screenshots/user-dashboard.png)

### Pandit Dashboard

# ![Pandit Dashboard](screenshots/pandit-dashboard.png)

### Admin Dashboard

# ![Admin Dashboard](screenshots/admin-dashboard.png)

### Puja Services

# ![Puja Services](screenshots/puja-services.png)

### Booking Management

# ![Booking Management](screenshots/booking-management.png)

---

## 🛠️ Technology Stack

### Frontend
- React.js
- JavaScript
- Tailwind CSS
- HTML5
- CSS3

### Backend
- Node.js
- Express.js
- REST APIs
- JWT Authentication

### Database & Storage
- MongoDB
- Cloudinary

### Deployment
- Netlify – Frontend Hosting
- Render – Backend Hosting

---

## 👥 User Roles & Functionalities

### 1. User
- Register and log in securely.
- Browse available puja services.
- Explore and book verified pandits.
- Manage personal profile.
- Manage and track bookings.

### 2. Pandit
- Manage pandit profile information.
- Access booking-related information.
- Manage assigned bookings.

### 3. Admin
- Access administrative dashboard.
- Manage users and pandits.
- Manage puja services.
- Manage booking information.

---

## 🏗️ Application Architecture

The application follows a client-server architecture.

```text
                  ┌──────────────────────┐
                  │      React.js        │
                  │   Frontend (Netlify) │
                  └──────────┬───────────┘
                             │
                         REST APIs
                             │
                  ┌──────────▼───────────┐
                  │      Node.js         │
                  │     Express.js       │
                  │   Backend (Render)   │
                  └──────┬────────┬──────┘
                         │        │
                ┌────────▼───┐ ┌──▼──────────┐
                │  MongoDB   │ │ Cloudinary  │
                │  Database  │ │Image Storage│
                └────────────┘ └─────────────┘
```

---

## 📂 Project Structure

```text
Pujanam-Production/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── services/
│   │   └── App.jsx
│   │
│   └── package.json
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
├── screenshots/
│
├── .gitignore
└── README.md
```

*Note: Adjust this structure to match the actual repository directories.*

---

## ⚙️ Installation & Setup

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm
- MongoDB or MongoDB Atlas account
- Cloudinary account

### 1. Clone the Repository

```bash
git clone https://github.com/bhushan0919/Pujanam-Production.git

cd Pujanam-Production
```

### 2. Backend Setup

```bash
cd backend

npm install
```

Create a `.env` file in the backend directory.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
CORS_ORIGIN=http://localhost:5173
```

Start the backend:

```bash
npm run dev
```

### 3. Frontend Setup

Open another terminal:

```bash
cd frontend

npm install
```

Configure the frontend environment variables in `.env` according to your API configuration.

```env
VITE_API_URL=http://localhost:5000
```

Start the frontend:

```bash
npm run dev
```

The application should now be available locally.

---

## 🔐 Security Practices

- JWT-based authentication.
- Role-based authorization.
- Protected API routes.
- Environment variables for sensitive credentials.
- CORS configuration for frontend-backend communication.
- Cloudinary-based image management.
- Never commit `.env` files or expose API credentials.

---

## 🚀 Deployment

| Component | Platform |
|---|---|
| Frontend | Netlify |
| Backend | Render |
| Database | MongoDB Atlas |
| Image Storage | Cloudinary |

**Live Frontend:** https://pujanam.netlify.app/

The frontend communicates with the deployed backend through configured API endpoints.

---

## 🔮 Future Improvements

- Online payment gateway integration.
- Advanced booking notifications.
- Improved booking calendar and availability management.
- Enhanced analytics and reporting.
- Additional astrology and kundali-related features.

---

## 👨‍💻 Developer

**Bhushan Gavhane**

Computer Engineering Graduate | Full Stack Developer

- GitHub: https://github.com/bhushan0919

---

<p align="center">
  ⭐ If you find this project interesting, consider giving it a star!
</p>

<p align="center">
  <b>Pujanam – Bringing traditional puja services closer through technology.</b>
</p>
