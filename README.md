# 🎮 PuzzleChain

Mystery Box Platform with Live Streaming

![Node.js](https://img.shields.io/badge/Node.js-18+-green)
![MongoDB](https://img.shields.io/badge/MongoDB-6+-green)
![React](https://img.shields.io/badge/React-18-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 🚀 Features

### Core Features
- ✅ User Authentication (JWT)
- ✅ Channels & Products Management
- ✅ Shopping Cart & Orders
- ✅ Mystery Boxes with Provably Fair RNG
- ✅ Live Streaming Support
- ✅ Payment Integration (Stripe + TON Wallet)

### Advanced Features
- ✅ Admin Dashboard
- ✅ Analytics & Reporting
- ✅ Redis Caching
- ✅ Email Notifications
- ✅ Multi-language Support (Arabic + English)
- ✅ PWA Support
- ✅ SEO Optimized

### Revenue Features
- ✅ Subscription Plans (Free, Basic, Premium, VIP)
- ✅ Affiliate System (Multi-level)
- ✅ Battle Pass
- ✅ Mystery Boxes
- ✅ Ads System

---

## 💻 Tech Stack

### Backend
- **Runtime:** Node.js 18+
- **Framework:** Express.js
- **Database:** MongoDB 6+
- **Cache:** Redis
- **Authentication:** JWT
- **Payment:** Stripe, TON Wallet

### Frontend
- **Framework:** React 18
- **Build Tool:** Vite
- **Styling:** Tailwind CSS
- **State:** Zustand
- **Routing:** React Router v6

### DevOps
- **Container:** Docker, Docker Compose
- **Proxy:** Nginx

---

## 🏃 Getting Started

### Prerequisites

- Node.js 18+
- MongoDB 6+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/mrabt3475-cpu/puzzlechain.git
cd puzzlechain

# Backend setup
cd backend
npm install
cp .env.example .env
# Edit .env with your configuration

# Frontend setup
cd ../frontend
npm install
```

### Running

```bash
# Backend (Terminal 1)
cd backend
npm run dev

# Frontend (Terminal 2)
cd frontend
npm run dev
```

The application will be available at:
- **Frontend:** http://localhost:5173
- **Backend:** http://localhost:3000
- **API:** http://localhost:3000/api

---

## 🐳 Docker

### Quick Start with Docker Compose

```bash
# Start all services
docker-compose up -d

# View logs
docker-compose logs -f

# Stop all services
docker-compose down
```

### Services

| Service | Port | Description |
|---------|------|-------------|
| MongoDB | 27017 | Database |
| Redis | 6379 | Cache |
| Backend | 3000 | API Server |
| Frontend | 5173 | Web App |
| Nginx | 80 | Reverse Proxy |

---

## 📚 API Documentation

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - Login
- `GET /api/auth/me` - Get current user

### Channels
- `GET /api/channels` - List channels
- `POST /api/channels` - Create channel
- `GET /api/channels/:id` - Get channel details

### Products
- `GET /api/products` - List products
- `POST /api/products` - Create product
- `GET /api/products/:id` - Get product details

### Orders
- `GET /api/orders` - Get user orders
- `POST /api/orders` - Create order

### Payment
- `POST /api/payment/stripe/checkout` - Create checkout session
- `POST /api/payment/ton/deposit` - Create TON deposit address

### Mystery Boxes
- `GET /api/boxes` - List boxes
- `POST /api/boxes/open` - Open a box

---

## 💰 Revenue

### Expected Monthly Revenue

| Source | Amount |
|--------|--------|
| Subscriptions | ~$37,474 |
| Ads | ~$10,000 |
| Affiliate | ~$5,000 |
| Battle Pass | ~$3,000 |
| Mystery Boxes | ~$2,000 |
| **Total** | **~$57,000/month** |

---

## 📄 License

MIT License - See [LICENSE](LICENSE) for details.

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📧 Contact

- Email: support@puzzlechain.com
- Website: https://puzzlechain.com

---

Made with ❤️ by PuzzleChain Team
