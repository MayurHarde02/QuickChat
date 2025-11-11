# 💬 QuickChat

A modern **real-time chat web application** built using **React (Vite)**, **Tailwind CSS**, and **Node.js (Express)**.  
QuickChat provides a smooth, minimal chat experience with responsive design, fast performance, and clean UI.

---

## 🚀 Features

- 🔐 **User Authentication** (login/signup flow)
- 💬 **Instant Messaging** (dynamic chat UI)
- 🕵️ **User Search** (find and chat instantly)
- 📱 **Responsive UI** (works beautifully on all devices)
- ☁️ **Environment Variables Protected** (.env used for secrets)
- 🎨 **Modern Glassmorphic Design** (Tailwind CSS + blur effects)

---

## 🧰 Tech Stack

**Frontend:**  
⚛️ React (Vite)  
🎨 Tailwind CSS  
🌐 Axios / Fetch API  
🔤 React Router DOM  

**Backend:**  
🟢 Node.js  
🚀 Express.js  
🗄️ MongoDB (depending on setup)  
🔐 dotenv for environment variables  

---

## ⚙️ Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/MayurHarde02/QuickChat.git
cd QuickChat
```

## ⚙️ 2️⃣ Install Dependencies

### 🧩 For Client
```bash
cd client
npm install
npm run dev
```
### 🧩 For Server
``` bash
cd ../server
npm install
npm start
```


---
## 🔑 Environment Variables

Create `.env` files in both **client** and **server** folders before running the app.
 
### 🧩 client/.env
```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_AUTH_DOMAIN=your_auth_domain
```
### 🧩 server/.env
PORT=5000
MONGODB_URI=your_database_connection_string
JWT_SECRET=your_secret_key


---

###📘 **Tip:**  
To make it look even cleaner, include a short line above this section, like:
Before running the app, make sure to install all dependencies and set up environment variables.
