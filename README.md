# 📦 E-commerce (Next.js 15 + MongoDB + Clerk)

This project provides a secure API endpoint for fetching orders placed by authenticated users. It uses **Next.js 15**, **MongoDB**, **Cloudinary** and **Clerk for authentication**.

---

## 📚 Features

- 🔐 Fetch orders for the currently logged-in user
- 🛡️ Secure route protected by Clerk authentication
- 🌐 Connects to a MongoDB database using Mongoose
- 📦 Populates related `Address` and `Product` data for each order
- 🚨 Graceful error handling

---

## ⚙️ Getting Started

### 1️⃣ Install dependencies:
```bash
npm install
```
### 2️⃣ Run the development server:
```bash
npm run dev
```
---
## 🛠️ Tech Stack

⚛️ Next.js 15 

🍃 MongoDB + Mongoose

🔐 Clerk (for authentication)

🚀 Optionally deploy on Vercel

📸 Cloudinary 

🔔 React Hot Toast

---

## 📊 Data Flow (Quick Overview)

Client 📱 → API Route (/api/orders) 📡 → Database (MongoDB) 🗄️ → API Response 📤 → Client




