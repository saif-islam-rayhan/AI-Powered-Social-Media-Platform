# AI-Powered-Social-Media-Platform(Full Stack)


This repository contains both **Frontend (Expo React Native)** and **Backend (Node.js API)** in a single monorepo.

---

# 🚀 Project Structure

```
Social-Media-Project/
│
├── Social-Media--main/     ← Frontend (Expo React Native App)
│     ├── app/
│     ├── package.json
│     ├── App.js
│     └── ...
│
└── SmartConnect-main/       ← Backend (Node.js + MongoDB API)
      ├── index.js
      ├── package.json
      ├── routes/
      ├── controllers/
      └── ...
```

---

# 📦 Install Dependencies

## 📱 Frontend (Expo App)
```
cd Social-Media--main
npm install
```

## 🖥 Backend (Node.js Server)
```
cd SmartConnect-main
npm install
```

---

# ▶ Start the Application

## 📱 Start Frontend (Expo)
```
cd Social-Media--main
npx expo start
```

## 🖥 Start Backend (Node.js)
```
cd SmartConnect-main
nodemon index.js
```

---

# 🛠 Technologies Used

### Frontend (Expo)
- React Native
- Expo Router
- Hooks & Components
- File-based routing

### Backend (Node.js)
- Express.js
- MongoDB / Mongoose
- JWT Authentication
- Nodemon (dev server)

---

# 🌐 Overview

- The mobile app UI is built using **Expo React Native**.
- The server API is built with **Node.js + Express.js**.
- Both parts are separated into two folders in the same GitHub repo for easier development.

---

# 📎 How to Update Code (Push to GitHub)

From the root folder:

```
git add .
git commit -m "Updated frontend + backend"
git push origin main
```

---

# ✨ Author
**Saif Islam Rayhan**
