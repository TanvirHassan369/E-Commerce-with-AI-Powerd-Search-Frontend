# 🛒 E-Commerce Frontend (Client)

The customer-facing frontend of a full-stack e-commerce platform. Built with React and Vite, featuring product browsing, cart management, checkout with payment integration, and AI-powered search.

---

## ✨ Features

- 🔐 User registration & login (JWT-based auth)
- 🏠 Home page with hero slider, category grid & product slider
- 🔍 Product search, filter & pagination
- 🤖 AI-powered product search modal
- 🛒 Shopping cart with Redux state persistence
- 💳 Checkout with **Stripe** payment integration
- 📦 Order tracking
- 👤 User profile & account management
- 🌙 Dark / Light theme toggle
- 📱 Fully responsive design

---

## 🧱 Tech Stack

| Technology | Purpose |
|---|---|
| React 18 + Vite | UI framework & build tool |
| Redux Toolkit + Redux Persist | State management |
| React Router v6 | Client-side routing |
| Tailwind CSS | Styling |
| Axios | API communication |
| Stripe | Payment processing |
| React Toastify | Notifications |
| Lucide React + React Icons | Icons |

---

## 📁 Project Structure

```
Client/
├── public/             # Static assets (images)
├── src/
│   ├── components/
│   │   ├── Home/       # HeroSlider, CategoryGrid, ProductSlider, etc.
│   │   ├── Layout/     # Navbar, Footer, CartSidebar, LoginModal, etc.
│   │   └── Products/   # ProductCard, Pagination, AISearchModal, etc.
│   ├── pages/          # Home, Cart, About, Contact, FAQ, etc.
│   ├── contexts/       # ThemeContext
│   ├── lib/            # Axios instance
│   ├── data/           # Static product data
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- Backend server running (see [Server README](../../ECommerce(SERVER)/Server/README.md))

### Installation

```bash
# Clone the repository
git clone https://github.com/TanvirHassan369/ecommerce-fullstack.git

# Navigate to client
cd "E-Commerce(CLIENT)/Client"

# Install dependencies
npm install

# Start development server
npm run dev
```

App runs at `http://localhost:5173`

### Environment Variables
Create a `.env` file in the `Client/` directory:
```
VITE_API_URL=http://localhost:5000
VITE_STRIPE_PUBLIC_KEY=your_stripe_public_key
```

---

## 🔗 Related

- 🖥️ [Server (Backend)](../../ECommerce(SERVER)/Server/README.md)
- 📊 [Admin Dashboard](../../ECommerce(Dashboard)/ecommerce-dashboard-template/README.md)
