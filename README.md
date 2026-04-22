# Seamless E-Commerce: Canadian E-Commerce Architecture (MVP)


[![Market: Canada](https://img.shields.io/badge/Market-Canada-red.svg)]()

## 💼 Business Overview
Seamless E-Commerce is a professional-grade E-Commerce prototype designed for the Canadian retail market. This project demonstrates a complete **Commercial MVP** (Minimum Viable Product) that bridges the gap between customer discovery and secure checkout.

### Key Business Features
* **Customer Trust Layer:** Secure User Authentication via **JSON Web Tokens (JWT)** for protected profile management.
* **Scalable Inventory:** Full CRUD (Create, Read, Update, Delete) capability for product management, supported by **Cloudinary** for high-performance image CDN delivery.
* **Market Readiness:** Designed for **CAD currency** and optimized for Canadian mobile/desktop users.
* **Administrative Oversight:** A dedicated Admin Dashboard to monitor sales, update inventory, and manage user orders in real-time.

## 🛠️ Technical Implementation
This project utilizes the **MERN Stack** (MongoDB, Express, React, Node.js) to ensure a high-performance, non-blocking user experience.

* **Frontend:** React 18+ with Vite for ultra-fast build times and production-ready optimization.
* **State Management:** Robust data handling using **Redux** and **Axios**.
* **Security:** Implementation of `.env` protection for sensitive API keys and database URI strings.
* **Payments:** Pre-configured architecture for **Stripe** integration.

## 🚀 Installation & Setup

1. **Clone & Install Backend**:
    ```bash
    cd backend
    npm install
    ```

2. **Clone & Install Frontend**:
    ```bash
    cd ../frontend
    npm install --legacy-peer-deps
    ```

3. **Configure Environment Variables**:
    Create a `.env` in the `backend` folder with your credentials (JWT Secret, MongoDB URI, Stripe/Cloudinary keys).

4. **Launch Application**:
    * **Backend:** `npm start` (Runs on port 4000)
    * **Frontend:** `npm run dev` (Runs on port 5173)

## 📦 MVP Status & Future Roadmap
This submission represents a **Phase 1 Technical Prototype**. 
* [x] Core API Architecture
* [x] Compiled Production Build (`dist` folder)
* [ ] Live Stripe Payment Gateway (Phase 2)
* [ ] Multi-region Tax Calculation logic (Phase 2)

## 📄 License
Distributed under the MIT License.

---
**Developer Note:** This project was developed as part of a Technical & Business Bonus Submission, showcasing advanced full-stack capabilities and commercial intent.