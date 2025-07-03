# 🍽️ Catering Service Management System

A modern, full-featured full-stack web application for catering businesses, built with:
- **Frontend:** React (catering/)
- **Backend:** Node.js + Express (backend/)
- **Database:** MongoDB (via Mongoose)
- User-friendly and scalable!

---

## 🚀 Features

- ✅ **User Authentication** (providers and customers)
- 🍽️ Service browsing & ordering (menu, cart, order placement)
- 📬 Messaging between customers & providers
- 📋 Provider dashboards for managing services & orders
- 🔒 Terms & Privacy pages included

---

## 🛠️ Tech Stack

- **Frontend:** React (Create React App), CSS modules/pages styling
- **Backend:** Node.js, Express, Mongoose, MongoDB
- **Auth:** JWT-based login/register (including `Login.js`)
- **HTTP Client:** Axios for API calls

---

## 📁 Project Structure

```
elite/
├── backend/
│   ├── config/          – database & env setup
│   ├── models/          – Mongoose schemas
│   ├── routes/          – Express endpoint definitions
│   ├── server.js        – app entry point
│   └── package.json
└── catering/
    ├── src/
    │   ├── pages/       – Login, Menu, Order, ProviderDashboard, etc.
    │   ├── reportWebVitals.js
    │   └── setupTests.js
    ├── public/
    └── package.json
```

---

## 💻 Getting Started

### 1. Install Dependencies

```bash
cd backend
npm install

cd ../catering
npm install
```

### 2. Environment Setup

Create `.env` files in both `backend/` and `catering/` with:

```
# backend/.env
PORT=5000
MONGO_URI=<your MongoDB connection string>
JWT_SECRET=<your secret key>
```

Frontend environment is optional but can include:
```
REACT_APP_BACKEND_URL=http://localhost:5000
```

### 3. Run Locally

```bash
# Terminal 1
cd backend
npm start

# Terminal 2
cd catering
npm start
```

- Backend runs at → `http://localhost:5000`
- Frontend runs at → `http://localhost:3000`

---

## 🌐 API Endpoints (Sample)

- `POST /api/auth/register` – Register new user  
- `POST /api/auth/login` – Login and receive JWT  
- `GET /api/services` – List all catering services  
- `POST /api/orders` – Create a new order  
- `GET /api/messages` – View chat threads

More details are available inside `backend/routes/`

---

## 📌 Future Improvements

- Payment integration (Stripe/PayPal)
- Role-based access control enhancements (Admin / Provider / User)
- Chat push notifications (Socket.io)
- UI polish with frameworks like Tailwind or Material-UI

---

## Author

**Tejaswini Thungathoorthi** – Full-stack enthusiast & developer  
📫 Find me on [LinkedIn](https://www.linkedin.com/in/tejaswini-thungathoorthi-9076b2295) or check out more projects on [GitHub](https://github.com/TejaswinisGit)!

---

