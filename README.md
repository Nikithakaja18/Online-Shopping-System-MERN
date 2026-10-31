# Online Shopping System — MERN

A user-friendly full-stack online shopping system using MongoDB, Express, React and Node.js.

## Features
- Responsive modern storefront
- Product search, categories and sorting
- Product details
- Persistent shopping cart
- Customer registration/login with JWT
- Checkout and Cash on Delivery order creation
- Customer order history
- Admin dashboard
- Admin product management
- Admin order-status management
- MongoDB/Mongoose data models
- Demo seed data

## Run

### Backend
```bash
cd server
npm install
```
Create `.env` from `.env.example`, then:
```bash
npm run seed
npm run dev
```

### Frontend
```bash
cd client
npm install
```
Create `.env` from `.env.example`, then:
```bash
npm run dev
```

Open the Vite URL, normally `http://localhost:5173`.

### Demo admin
Email: `admin@shopnest.com`
Password: `Admin@123`

## Environment
Backend:
`MONGO_URI=mongodb://127.0.0.1:27017/online_shopping`
`JWT_SECRET=change_this_secret`
`CLIENT_URL=http://localhost:5173`

Frontend:
`VITE_API_URL=http://localhost:5000/api`

For production, add a real payment gateway, image storage, rate limiting, stronger validation, HTTPS and production secrets.
