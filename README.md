# E---commerce-app
A full-stack e-commerce web application with product listings, shopping cart, user authentication, order management, and payment integration. Built for a seamless online shopping experience.
> **🚀 A blazing-fast, fully responsive e-commerce platform built with the MERN stack.**

[🌐 Live Demo](#) · [🐛 Report Bug](../../issues) · [✨ Request Feature](../../issues)

</div>

---

## 📋 Table of Contents
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started](#-getting-started)
- [📁 Project Structure](#-project-structure)
- [🔌 API Endpoints](#-api-endpoints)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📬 Contact](#-contact)

---

## ✨ Features

| | Feature | Description |
|---|---|---|
| 🛍️ | **Product Catalog** | Browse with filters, sorting & search |
| 🛒 | **Shopping Cart** | Real-time cart with quantity management |
| 🔐 | **Authentication** | JWT-based login, register & Google OAuth |
| 💳 | **Payments** | Secure checkout via Stripe |
| 📦 | **Order Tracking** | Real-time order status updates |
| 🧑‍💼 | **Admin Dashboard** | Manage products, users & orders |
| ⭐ | **Reviews & Ratings** | User-generated product reviews |
| 📱 | **Fully Responsive** | Mobile, tablet & desktop ready |
| 🌙 | **Dark Mode** | Light and dark theme toggle |
| 🔍 | **Advanced Search** | Autocomplete & smart filters |

---

## 🛠️ Tech Stack

### Frontend
| Tech | Purpose |
|------|---------|
| React | UI Library |
| Redux Toolkit | State Management |
| Tailwind CSS | Styling |
| Axios | HTTP Client |

### Backend
| Tech | Purpose |
|------|---------|
| Node.js | Runtime |
| Express.js | Web Framework |
| MongoDB | Database |
| Mongoose | ODM |

### Services
| Tech | Purpose |
|------|---------|
| Stripe | Payments |
| Cloudinary | Image Hosting |
| JWT | Authentication |
| Docker | Containerization |

---

## 🚀 Getting Started

### Prerequisites
```bash
node  >= 18.0.0
npm   >= 9.0.0
git   >= 2.30.0
```

### Installation

```bash
# 1. Clone the repo
git clone https://github.com/your-username/E-commerce-app.git
cd E-commerce-app

# 2. Install backend dependencies
cd server && npm install

# 3. Install frontend dependencies
cd ../client && npm install
```

### Environment Variables

**`server/.env`**
```env
PORT=5000
NODE_ENV=development
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=30d
STRIPE_SECRET_KEY=sk_test_xxxx
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

**`client/.env`**
```env
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_STRIPE_PUBLIC_KEY=pk_test_xxxx
```

### Run the App

```bash
# Run both client & server together (from root)
npm run dev

# Or separately:
cd server && npm run dev      # http://localhost:5000
cd client && npm start        # http://localhost:3000
```

---

## 📁 Project Structure
E-commerce-app/
├── 📂 client/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── redux/
│       ├── hooks/
│       ├── services/
│       └── utils/
│
├── 📂 server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── utils/
│
├── .gitignore
├── docker-compose.yml
└── README.md

---

## 🔌 API Endpoints

### Auth
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register user |
| POST | `/api/auth/login` | Login user |
| GET | `/api/auth/logout` | Logout user |
| GET | `/api/auth/me` | Get current user |

### Products
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/products` | Get all products |
| GET | `/api/products/:id` | Get single product |
| POST | `/api/products` | Create product *(Admin)* |
| PUT | `/api/products/:id` | Update product *(Admin)* |
| DELETE | `/api/products/:id` | Delete product *(Admin)* |

### Orders
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/orders` | Place new order |
| GET | `/api/orders/mine` | Get my orders |
| GET | `/api/orders/:id` | Get order by ID |
| PUT | `/api/orders/:id/pay` | Mark as paid |

---

## 🤝 Contributing

1. Fork the project
2. Create your branch → `git checkout -b feature/AmazingFeature`
3. Commit changes → `git commit -m "feat: add AmazingFeature"`
4. Push → `git push origin feature/AmazingFeature`
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for details.

---

## 📬 Contact

<div align="center">

**VIVEK CHAUDHARY** — SOFTWARE DEVELOPER

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vivekchauhan000)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-profile)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@gmail.com)

⭐ **Star this repo if you found it helpful!** ⭐

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
