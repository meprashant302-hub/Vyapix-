# 📦 VYAPIX Frontend

A modern and responsive inventory management frontend built using React, Vite, and Tailwind CSS.

This project serves as the frontend interface for the Vyapix business management system, designed to simplify inventory tracking, sales management, and product monitoring through a clean and intuitive UI.

> ⚠️ This project is forked from the original repository and customized for educational and learning purposes.

---

# 🚀 Project Overview

Vyapix Frontend provides a fast, scalable, and user-friendly dashboard interface for managing:

- Inventory records
- Product stock levels
- Sales monitoring
- Business reports
- Authentication flows
- Dashboard analytics

The application focuses on performance, modular architecture, and responsive design to ensure a smooth experience across desktop and mobile devices.

---

# ✨ Core Features

## ⚡ Fast Frontend Architecture
Built with React + Vite for rapid development and optimized production builds.

## 🎨 Modern UI Styling
Styled using Tailwind CSS with reusable utility classes and responsive layouts.

## 🔗 API Integration
Uses Axios for seamless communication with backend services such as:

- Authentication APIs
- Inventory APIs
- Sales APIs
- Product management APIs

## 📱 Fully Responsive Design
Optimized layouts for desktops, tablets, and mobile devices.

## 🌙 Dark Mode Support
Includes theme toggle functionality for enhanced user experience.

## 🧩 Reusable Component System
Well-structured reusable components for maintainability and scalability.

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React | Frontend UI Library |
| Vite | Development & Build Tool |
| Tailwind CSS | Styling Framework |
| Axios | API Communication |
| JavaScript (ES6+) | Application Logic |

---

# 📁 Project Structure

```bash
vyapix-frontend/
│
├── public/
│
├── src/
│   ├── assets/                    # Static assets (icons, images)
│   │
│   ├── components/                # Reusable UI components
│   │   ├── About.jsx
│   │   ├── BarcodeScanner.jsx
│   │   ├── Btn-toggle.jsx
│   │   ├── Greeting.jsx
│   │   ├── Header.jsx
│   │   ├── Intro.jsx
│   │   ├── InventoryManager.jsx
│   │   ├── Loading.jsx
│   │   ├── Login.jsx
│   │   ├── loginbar.jsx
│   │   ├── MakeSales.jsx
│   │   ├── MaxSales.jsx
│   │   ├── Menu.jsx
│   │   ├── OutofStock.jsx
│   │   ├── OverViewBox.jsx
│   │   ├── Signup.jsx
│   │   └── components.css
│   │
│   ├── Pages/                     # Main application pages
│   │   ├── Afterlogin.jsx
│   │   ├── Beforelogin.jsx
│   │   ├── Dashboard.jsx
│   │   ├── Inventory.jsx
│   │   ├── LowStock.jsx
│   │   ├── Report.jsx
│   │   ├── Sales.jsx
│   │   └── ...
│   │
│   ├── services/                  # API helper functions (optional)
│   │
│   ├── App.jsx                    # Root component
│   ├── App.css
│   └── main.jsx
│
├── package.json
├── vite.config.js
└── README.md
```

---

# 🔧 Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/vyapix-frontend.git

cd vyapix-frontend
```

---

## 2️⃣ Install Dependencies

```bash
npm install
```

---

## 3️⃣ Start Development Server

```bash
npm run dev
```

---

## 4️⃣ Create Production Build

```bash
npm run build
```

---

# 🔗 API Integration Example

```javascript
import axios from "axios";

const API = axios.create({
  baseURL: "https://your-backend-api.com/api",
});

// Authentication
export const loginUser = (data) => API.post("/login", data);

// Inventory
export const getInventory = () => API.get("/inventory");

// Sales
export const getSales = () => API.get("/sales");
```

---

# 📚 Application Pages

| Page | Description |
|---|---|
| `Dashboard.jsx` | Displays business overview, analytics, and summary cards |
| `Inventory.jsx` | Manages product inventory records |
| `LowStock.jsx` | Shows products with low stock quantity |
| `Sales.jsx` | Displays sales records and transactions |
| `Report.jsx` | Generates reports and analytics |
| `Afterlogin.jsx` | Landing page after user authentication |
| `Beforelogin.jsx` | Public landing page before login |

---

# 🧩 Reusable Components

| Component | Purpose |
|---|---|
| `Login.jsx` | User login form |
| `Signup.jsx` | User registration form |
| `Menu.jsx` | Sidebar navigation and logout |
| `Header.jsx` | Top navigation/header section |
| `Loading.jsx` | Loading animation/screen |
| `InventoryManager.jsx` | Inventory-related business logic |
| `Greeting.jsx` | Welcome section |
| `OutofStock.jsx` | Out-of-stock product preview |
| `OverViewBox.jsx` | Dashboard statistics cards |
| `MaxSales.jsx` | Sales performance summary |
| `Btn-toggle.jsx` | Theme and visibility toggles |

---

# 🎯 Project Goals

This project was developed to practice and improve skills in:

- Frontend development
- Component-based architecture
- API integration
- Responsive UI design
- State management concepts
- Dashboard development

---

# 🚀 Future Improvements

Planned enhancements include:

- Product image uploads
- Advanced search & filtering
- Chart integration using Recharts/Chart.js
- Role-based authentication (Admin/Staff)
- Barcode scanning improvements
- Local data caching
- Performance optimization

---

# 🤝 Contributing

Contributions are welcome.

If you'd like to improve the UI, optimize performance, or add features:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

# 📘 Learning Resources

Recommended resource for improving full-stack development skills:

https://www.geeksforgeeks.org/courses/full-stack-web-dev-skill-up

---

# 📄 License

This project is intended for educational and learning purposes only.  
All original credits belong to the respective repository owners.

