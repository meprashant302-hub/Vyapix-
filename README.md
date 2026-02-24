This project is forked from original repositary and modified for learning purpose.





📦 VYAPIX — Frontend

Vyapix is a lightweight, fast, and responsive frontend interface built using React (Vite), Tailwind CSS, and Axios for API communication.
This repository contains only the UI layer, while the backend APIs (authentication, product data, stock, sales, etc.) are handled separately.

---

🚀 Overview

The goal of Vyapix is to offer an intuitive interface for businesses to manage and view:

- Inventory
- Sales
- Low stock notifications
- Reports
- Login/Signup flows
- Product overview dashboards

The UI is modular, clean, and optimized for both desktop and mobile.

---

✨ Key Features

- React + Vite: Extremely fast dev environment & optimized production builds
- Tailwind CSS: Modern and scalable utility-based styling
- Axios API Integration: Connects to backend for login, stock, sales, and product data
- Modular Folder Structure: Clean separation of components & pages
- Responsive Sidebar + Dark Mode Support
- Reusable Components: Login, Signup, Menu, Loading, Header, Buttons, etc.

---

📁 Project Structure (Based on Your Actual Repo)

vyapix-frontend/
│
├── public/
│
├── src/
│   ├── assets/                   # Static icons, images used in UI
│   │ 
│   ├── components/               # Reusable UI components
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
│   │   ├── Menu.jsx              # Sidebar + profile + logout
│   │   ├── OutofStock.jsx
│   │   ├── OverViewBox.jsx
│   │   ├── Signup.jsx
│   │   └── components.css
│   │
│   ├── Pages/                    # Main application screens
│   │   ├── Afterlogin.jsx
│   │   ├── Beforelogin.jsx
│   │   ├── Dashboard.jsx
│   │   ├── Inventory.jsx
│   │   ├── LowStock.jsx
│   │   ├── Report.jsx
│   │   ├── Sales.jsx
│   │   └── …
│   │
│   ├── services/ (if exists)     # Axios API helpers (recommended)
│   │
│   ├── App.jsx                    # Root component
│   ├── App.css
│   └── main.jsx
│
├── package.json
├── vite.config.js
└── README.md

---

🔧 Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/your-username/vyapix-frontend.git
cd vyapix-frontend

2️⃣ Install dependencies

npm install

3️⃣ Start the development server

npm run dev

4️⃣ Build for production

npm run build

---

🔗 API Integration (Axios Example)

import axios from "axios";

const API = axios.create({
  baseURL: "https://your-backend-api.com/api",
});

// Login
export const loginUser = (data) => API.post("/login", data);

// Fetch inventory
export const getInventory = () => API.get("/inventory");

// Fetch sales data
export const getSales = () => API.get("/sales");

---

📚 Pages & Components Explained

Pages/

Page| Purpose
"Dashboard.jsx"| Main overview (sales, inventory summary, charts, cards)
"Inventory.jsx"| Full inventory listing
"LowStock.jsx"| Items running low
"Sales.jsx"| Sales data + sale creation
"Report.jsx"| Reports & analytics
"Afterlogin.jsx"| User landing page after successful login
"Beforelogin.jsx"| Landing page before login

Components/

Component| Purpose
"Login.jsx"| Login popup/box
"Signup.jsx"| Signup form
"Menu.jsx"| Sidebar navigation (with profile + logout)
"Header.jsx"| Top navigation bar
"Loading.jsx"| Loading screen
"InventoryManager.jsx"| Internal inventory logic
"Greeting.jsx"| Welcome message
"OutofStock.jsx"| Out-of-stock preview
"OverViewBox.jsx"| Dashboard cards
"MaxSales.jsx"| Sales summary
"Btn-toggle.jsx"| Theme/visibility toggles

---

📚 Future Enhancements

- Full image support for products
- Upload product photos
- Role-based access (Admin / Staff)
- Filters + search improvements
- Charts integration (Recharts/Chart.js)
- Local caching for speed

---

🤝 Contributing

Feel free to open issues or PRs that improve UI, code quality, or performance.

---

📘 Recommended Learning

Continue mastering full-stack development:
https://www.geeksforgeeks.org/courses/full-stack-web-dev-skill-up

---


