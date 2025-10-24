# Webpez – Referral & Credit System

## 📌 Project Overview
**Webpez** is a full-stack Referral & Credit System built as a digital product platform. Users can register, share referral links, earn credits on referrals’ first purchases, and track all referral activity through a responsive dashboard. This project demonstrates a scalable, modular full-stack application with clean architecture, secure authentication, and thoughtful engineering practices.

---

## ✅ Core Features

### User Authentication
- Secure registration, login, and logout
- Passwords hashed using **bcrypt**
- JWT-based authentication with HTTP-only cookies

### Referral Management
- Each user receives a **unique referral link**
- Referral relationships tracked upon registration
- Referral status recorded (registered vs converted)
- **2 credits** awarded to both users on the first purchase only
- Prevents double-crediting

### Purchase Simulation
- “Buy Product” button to simulate purchases
- Only the first purchase of a referred user triggers credit rewards

### User Dashboard
- Total Referred Users
- Converted Users (who purchased)
- Total Credits Earned
- Unique referral link with copy/share option

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js 15, TypeScript, Tailwind CSS, Framer Motion |
| Backend | Node.js, Express.js, TypeScript |
| Database | MongoDB + Mongoose |
| State Management | Zustand |
| Validation | Zod (frontend & backend) |
| Authentication | JWT + bcrypt |

---

## 📂 Project Structure

