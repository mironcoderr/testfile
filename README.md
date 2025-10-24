# 📌 webpez – Referral & Credit System (Full Stack)
This project is a full-stack Referral & Credit System built as part of a mid-level developer assignment. The system simulates a digital product platform (e.g., e-book/templates store) where users can register, invite others using a referral link, earn credits on referred users’ first purchases, and track referral activity through a dashboard.

✅ Core Features
🔐 User Authentication

Register, login, and logout securely

Passwords hashed using bcrypt

Authentication managed with JWT tokens (HTTP-only cookies)

🏷️ Referral Management

Each user automatically receives a unique referral link

When a new user registers using the referral link, the relationship is recorded

Referral statuses tracked (registered vs converted)

Both referrer and referred users earn 2 credits on the referred user’s first purchase only

Double-credit protection (only first purchase is rewarded)

🛒 Purchase Simulation

Users can simulate buying a product using a "Buy Product" button

Only the first purchase of a referred user triggers credit rewards
