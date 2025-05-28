# 🛒 Shop-Cart

A modern e-commerce web app built with the MERN stack.

---
### Prerequisites

- Node.js (v14+)
- MongoDB

## 🚀 Tech Stack & Tools

| Frontend | Backend | Database | Auth | UI | Dev Tools |
|:--------:|:-------:|:--------:|:----:|:--:|:---------:|
| ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) | ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=fff) | ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?logo=mongodb&logoColor=fff) | ![JWT](https://img.shields.io/badge/JWT-000?logo=jsonwebtokens) | ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=fff) | ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?logo=visual-studio-code&logoColor=fff) |
| ![React Router](https://img.shields.io/badge/React_Router-CA4245?logo=react-router&logoColor=fff) | ![Express](https://img.shields.io/badge/Express-000?logo=express&logoColor=fff) |  |  |  | ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff) |
| ![Axios](https://img.shields.io/badge/Axios-5A29E4?logo=axios&logoColor=fff) |  |  |  |  |  |

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
# See full setup in the main README section above
```
## 📁 Project Folder Structure
shop-cart/ │ ├── client/ # 🖥️ React frontend │ ├── public/ │ └── src/ │ ├── api/ # 🔗 API calls │ ├── assets/ # 🖼️ Images and static files │ ├── components/ # 🧩 Reusable UI components │ │ └── headers/ # ⤷ Header component │ ├── pages/ # 📄 Page components (Home, Cart, etc.) │ ├── GlobalState.js # 🌐 Global state management │ └── App.js # 🚦 App entry point │ ├── server/ # 🗄️ Express backend │ ├── controllers/ # 🧠 Route logic │ ├── middleware/ # 🛡️ Auth, error handling, etc. │ ├── models/ # 🗃️ Mongoose models │ ├── routes/ # 🚏 API routes │ └── server.js # 🚀 Server entry point │ ├── .env # 🔑 Environment variables ├── package.json # 📦 Project metadata (root) └── README.md # 📘 Project documentation

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


