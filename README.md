# KHTOPUP — Complete Full Auto-Store Launch Guide

This package contains everything needed to run **KHTOPUP** live on the internet with real ABA PayWay KHQR payments, wholesale game top-up APIs (Smile.One / MooGold), and instant Telegram Bot notifications.

## Files Included
- `index.html` — Complete mobile-responsive storefront, currency switcher (USD/KHR), order tracker, and PIN-protected Admin Dashboard.
- `server.js` — Node.js + Express backend server with ABA PayWay KHQR QR generator, payment webhook receiver, Smile.One auto-top-up dispatcher, Telegram Bot alerts, and JSON database persistence.
- `package.json` — Dependencies list (`express`, `cors`).

## 3 Steps to Go Live Online (Free / Low Cost)
1. **Create a Telegram Bot (2 Minutes)**
   - Message `@BotFather` on Telegram, run `/newbot`, and copy your **Bot Token**.
   - Add the bot to your admin group or DM it, then get your **Chat ID** via `@userinfobot`.
2. **Deploy to Render.com or Railway.app (5 Minutes)**
   - Upload `index.html`, `server.js`, and `package.json` to a free GitHub repository.
   - Create a new **Web Service** on [Render.com](https://render.com) or [Railway.app](https://railway.app) connected to that repo.
   - Start Command: `npm start`
   - Once deployed, you get a live `https://your-site.onrender.com` URL (and you can attach your custom `.com` or `.kh` domain).
3. **Enter Your API Keys in the Admin Panel**
   - Open your live website, tap **Admin & API**, enter the default PIN `2026` (change it immediately in **Backend & API Keys**), paste your **Telegram Bot Token**, **ABA PayWay Merchant ID / Key**, and **Smile.One UID / Key**, and click **Save & Connect Live Backend**.
