# Zerodha
# Zerodha-Clone Project

A full-stack clone of the Zerodha trading platform, built for learning and project-demonstration purposes.  
This project replicates core UI flows and backend logic of a stock-brokerage dashboard.

---

## 🧾 Project Overview

This repository includes:  
- Front-end application (React) for login/signup, dashboard, watchlist, orders, holdings, etc.  
- Back-end API (Node.js + Express + MongoDB) managing users, trades, portfolio.  
- Modular code structure for scalability and maintainability.  
- Responsive UI with emphasis on user experience.

---

## 📋 Features

- User authentication: register, login, secure password hashing, JWT tokens.  
- Dashboard: view portfolio value, holdings, P&L, orders.  
- Orders & trades: place buy/sell, view history, track status.  
- Watchlist: add/remove stocks, view simulated real-time data.  
- Responsive design: works on desktop & mobile.  
- Modular architecture: clearly separated frontend/backend folders.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, React Router, Axios, CSS / Tailwind (or your chosen styling)  
- **Backend:** Node.js, Express.js, MongoDB (via Mongoose)  
- **Auth:** JWT tokens, bcrypt for password hashing  
- **Other:** REST APIs, modular folder structure, environment configuration  

---

## 📂 Project Structure (typical)

/frontend
/src
/components
/pages
/assets
App.js
index.js

/backend
/models # User, Order, Portfolio schemas
/routes # auth, orders, portfolio APIs
/controllers # business logic
server.js

.env # environment variables (backend)


---

## 🚀 Getting Started

### 1. Clone this repository
```bash
git clone https://github.com/shalz510/zerodha.git
cd zerodha

2. Install dependencies

Backend:
cd backend
npm install
Frontend:
cd ../frontend
npm install
3. Configure environment variables

Inside the backend/ folder create a .env file with:
MONGO_URI=<your-mongodb-connection-string>
JWT_SECRET=<your-jwt-secret>
PORT=5000
4. Run the apps

Backend:
cd backend
npm start
Frontend:
cd frontend
npm start
Open your browser at http://localhost:3000 (or the port you configured) to view the app.

Future Enhancements

Integrate live market API (to replace mock/simulated data).

Add WebSocket for real-time updates (prices, orders).

Enable more comprehensive trade types (F&O, margin, etc.).

Add user settings, notifications, themes.

Deploy to cloud (Heroku, Vercel, AWS) for a live demo.

Author

Shalini (shalz510)
Full-Stack Developer | Student | Passionate about building trading & finance apps

License

This project is licensed under the MIT License — see the LICENSE file for details.


