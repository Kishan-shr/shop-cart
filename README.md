# 🛒 Shop-Cart

A modern e-commerce web app built with the MERN stack.

---
### Prerequisites

- Node.js (v14+)
- MongoDB

## 🚀 Tech Stack

### 🖥️ Frontend
- ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) React
- ![React Router](https://img.shields.io/badge/React_Router-CA4245?logo=react-router&logoColor=fff) React Router
- ![Axios](https://img.shields.io/badge/Axios-5A29E4?logo=axios&logoColor=fff) Axios
- ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=fff) Tailwind CSS

### 🗄️ Backend
- ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=fff) Node.js
- ![Express](https://img.shields.io/badge/Express-000?logo=express&logoColor=fff) Express.js
- ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?logo=mongodb&logoColor=fff) MongoDB
- ![Mongoose](https://img.shields.io/badge/Mongoose-880000?logo=mongoose&logoColor=fff) Mongoose
- ![JWT](https://img.shields.io/badge/JWT-000?logo=jsonwebtokens) JSON Web Token (JWT)
- ![bcrypt](https://img.shields.io/badge/bcrypt-004488?logo=lock&logoColor=fff) bcrypt

### 🛠️ Dev Tools
- ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?logo=visual-studio-code&logoColor=fff) VS Code
- ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff) Git

---

## ✨ Features

- 🔐 User authentication (login/register/logout)
- 🛍️ Product listing, filtering, and detail view
- 🛒 Shopping cart with live updates
- 📦 Order history for users
- 🛠️ Admin dashboard for product/category management
- 📱 Responsive UI

---

## 📦 Getting Started

```sh
git clone https://github.com/Kishan-shr/shop-cart.git
cd shop-cart
```

## 📁 Project Folder Structure
shop-cart/
├── 📦 client/                    # React frontend
│   ├── 🌐 public/                # Static files (index.html, icons, etc.)
│   └── 💻 src/
│       ├── 🎨 assets/           # Images, fonts, and styles
│       ├── 🧩 components/       # Reusable UI components
│       ├── 📄 pages/            # Route-level page components
│       ├── 🔌 services/         # API interaction layer (Axios, fetch)
│       ├── 🧠 context/          # React Contexts and Providers
│       ├── 🛠️ App.js
│       └── 🧬 index.js
│
├── 🔧 server/                   # Node.js & Express backend
│   ├── ⚙️ config/              # Config files (e.g., DB connection)
│   ├── 🧠 controllers/         # Route handler logic
│   ├── 📦 models/             # Mongoose schemas/models
│   ├── 🚏 routes/             # API endpoints
│   ├── 🧰 middleware/         # Custom middleware (auth, error handling)
│   ├── 🧪 utils/              # Helper functions and utilities
│   └── 🚀 server.js           # Entry point for the backend
│
├── 🔐 .env                      # Environment variables
├── 📄 .gitignore                # Files to ignore in Git
├── 📦 package.json              # NPM project metadata and scripts
├── 📘 README.md                 # Project documentation
└── 🪪 LICENSE                   # License file


## Install Dependencies
```
Client
cd Client
npm install

Server
cd ../server
npm install

```
## Setup environment variables

```Create a .env file in the server directory:
MONGODB_URL=your_mongodb_connection_string
PORT=5000
```
## Run the application
```
Start Backend
cd server
npm start

Start Frontend
cd ../client
npm start

```
## License
```
MIT
```


