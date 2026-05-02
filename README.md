# 🌾 Agricultural Price Advisor System (APAS)

> **Empowering small-scale producers with data-driven pricing and market transparency.**

APAS is a web-based platform designed to bridge the information gap for farmers. By providing real-time market trends, AI-powered advisory services, and precise profit margin simulators, the system ensures farmers can maximize their returns and navigate market volatility with confidence.

---

## 🚀 Quick Links
[Features](#-key-features) • [User Roles](#-user-types) • [Interface](#-farmer-interface) • [Security](#-security-features) • [Getting Started](#-getting-started)

---

## 🌟 Key Features

| Feature | Description |
| :--- | :--- |
| **📈 Live Market Ticker** | Real-time price updates for major crops (Wheat, Corn, Soybeans, etc.) with color-coded trend indicators. |
| **🧮 Profit Simulator** | A cost-plus pricing model that factors in production costs, risk adjustments, and desired margins to calculate optimal selling prices. |
| **🤝 Direct Marketplace** | A streamlined interface for direct trading, removing unnecessary intermediaries to improve farmer revenue. |
| **🤖 AI Chatbot** | A dedicated agricultural advisor trained to answer pricing and best-practice queries in natural language. |
| **📲 SMS Alert System** | One-way system notifications and price threshold alerts delivered directly to mobile devices via Twilio. |

---

## 👥 User Types

### 👨‍🌾 Farmers
* **Market Insights:** View real-time prices and historic trends.
* **Calculators:** Use the **Profit Margin Simulation** tool to input specific production costs and risk factors.
* **Advisory:** Access the AI Chatbot for data-driven farming advice.
* **Subscriptions:** Manage one-way SMS alerts for specific crop thresholds.

### 🔑 Administrators
* **Product Control:** Manage crop types and units of measurement.
* **Market Data:** Record and update district-specific prices and history.
* **User Management:** Oversee farmer profiles and monitor geographic distribution of users.

---

## 🛠️ Tech Stack

Built with a robust, modern architecture:
* **Backend:** PHP Laravel
* **Database:** MySQL
* **Frontend:** React / Blade (Responsive Design)
* **Communications:** Twilio SMS API
* **Deployment:** GitHub Pages / Custom Domain (`agric-user.com`)

---

## 🖥️ Getting Started

### 1. Landing Page
The landing page features a **Live Market Ticker** and a clear call to action for users to register or sign in.

### 2. Registration & Login
* **Browser-Based:** Registration and login are handled via the web interface. 
* **Role Selection:** Users specify their role (Farmer or Admin) during signup.
* **Verification:** Email verification is required to activate the account.

### 3. Navigation
The system uses a persistent top navigation bar and role-specific sidebar menus for quick access to the **Profit Simulator**, **Service Discovery**, and **Subscription Management**.

---

## 🔒 Security Features

* **Role-Based Access Control (RBAC):** Ensures data integrity between Farmers and Admins.
* **Secure Authentication:** Built using Laravel’s standard authentication protocols.
* **One-Way Notifications:** System-to-user SMS ensures farmers receive verified pricing updates.
* **Responsive Design:** Optimized for mobile, tablet, and desktop browsers.

---

## 📖 Documentation & Support

* **In-App Help:** Use the chatbot for immediate assistance with system features.
* **Technical Support:** Contact details and documentation links are located in the site footer.

**Last Updated:** `2026-05-02`  
**Project Identifier:** `agri-project`
