# 🚀 KNOX App

KNOX is a full‑stack web application that allows users to **create, manage, and interact with AI‑powered characters**. Each character has its own personality, greeting, and behavior, making conversations immersive and dynamic.

---

## ✨ Features

* 🔐 **User Authentication** (Login / Register / Logout)
* 🧠 **AI Character Creation**

  * Name, description, category
  * Personality prompt
  * Custom greeting message
* 💬 **Real‑time Chat with Characters**
* 🌍 **Public & Private Characters**
* 🖼️ **Avatar Upload Support**
* ⚡ **Modern UI with Tailwind CSS**
* 🔄 **RESTful API Architecture**

---

## 🛠️ Tech Stack

### Frontend

* **React.js** (Vite)
* **Tailwind CSS**
* **Axios**
* **React Router DOM**
* **Context API** (User State Management)

### Backend

* **Node.js**
* **Express.js**
* **MongoDB Atlas**
* **Mongoose**
* **JWT Authentication**
* **Cookie‑based Sessions**

### AI / Chat

* AI‑powered chat responses (LLM‑based)

---

## 📂 Project Structure

```
KNOX/
├── client/              # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── api/
│   │   └── App.jsx
│   └── vite.config.js
│
├── server/              # Backend API
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the **server** directory:

```env
PORT=5000
MONGO_URI=your_mongodb_atlas_uri
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:5173
```

---

## ▶️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://https://github.com/proffessor688-dev/KNOX.git/knox-app.git
cd knox-app
```

### 2️⃣ Install Dependencies

#### Frontend

```bash
cd client
npm install
npm run dev
```

#### Backend

```bash
cd server
npm install
npm run dev
```

---

## 🔑 Authentication Flow

* User logs in
* JWT is generated and stored in HTTP‑only cookies
* Protected routes verify authentication
* User data is available via Context API

---

## 📡 API Endpoints (Sample)

### Auth

* `POST /api/auth/register`
* `POST /api/auth/login`
* `POST /api/auth/logout`
* `GET /api/auth/me`

### Characters

* `POST /api/characters/add`
* `GET /api/characters`
* `GET /api/characters/:id`
* `PUT /api/characters/:id`
* `DELETE /api/characters/:id`

### Chat

* `POST /api/chat/send`

---

## 🎨 UI Highlights

* Glassmorphism design
* Smooth transitions
* Responsive layout
* Dark theme by default

---

## 🧪 Future Enhancements

* 🔊 Voice‑based chat
* 🤝 Character sharing
* ⭐ Character rating system
* 🧩 Plugin‑based personalities
* 📱 Mobile App Version

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Shubham Vats**
B.Tech Student | Full‑Stack Developer

---

⭐ If you like KNOX, don’t forget to star the repository!

