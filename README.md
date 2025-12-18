# 🎭 MoodMate – Mood-Based Content Generator

A personalized mood-tracking web application that reacts to your emotions and generates content (quotes, tasks, music suggestions) based on how you feel.

Built with the **MERN** Stack (MongoDB, Express, React, Node.js).

---

## 🎯 Project Overview

MoodMate is a full-stack mood-based application that helps users track their emotions, journal their thoughts, and receive personalized content based on their mood.

The project focuses on:

✅ Emotional awareness

✅ Interactive UI

✅ Mood visualization

✅ Personalized content generation

---

## 🌟 Key Features

🧠 Mood Tracking - Users can select how they feel using a colorful, animated mood slider.

😀 Reacting Avatar - A dynamic avatar changes its expression based on mood.

📝 Mood Journal - Write thoughts about your day and save entries.

💬 Personalized Content - AI-style generator provides mood-matched:
  - Quotes
  - Tasks / challenges
  - Music suggestions 🎵

📜 Mood History - View previously saved moods, notes, and content.

👤 Authentication

  - Login / Register
  - JWT-based auth
  - Logout functionality

🎨 Interactive UI

  - Beautiful gradients
  - Animated cards
  - Smooth transitions
  - Modern button styles

---

## 🛠 Tech Stack

**Frontend**
- React.js
- React Router
- Axios
- Custom CSS (Glassmorphism + Neon gradients)

**Backend**
- Node.js
- Express.js
- JWT Authentication
- CORS + dotenv

**Database**
- MongoDB + Mongoose

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/moodmate.git
cd moodmate
```

### 2️⃣ Install Backend Dependencies
```bash
cd backend
npm install
```

### 3️⃣ Install Frontend Dependencies
```bash
cd ../frontend
npm install
```

---

## 🔐 Environment Variables

Create a .env file inside the backend folder:
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## 🚀 Running the Project

### 🟢 Start Backend Server

```bash
cd backend
npm run dev
```

### 🔵 Start Frontend React App

```bash
cd frontend
npm start
```

### The App Runs At:

```bash
Frontend → http://localhost:3000  
Backend  → http://localhost:5000  
```

---

## 📡 API Routes

### 🔐 Authentication

| Method | Route | Description |
|----------|------------|------------|
| POST | /api/auth/register | Register new user |
| POST | /api/auth/login | Login user |

### 😄 Mood Entries

| Method | Route | Description |
|----------|------------|------------|
| POST | /api/moods | Save mood entry |
| GET | /api/moods | Retrieve all mood entries |

---

## 🔮 Future Improvements

- AI-generated suggestions
- Spotify API integration for real music
- Mood analytics graph
- Dark/light theme switch
- Smarter emoji/avatar reactions
- Mobile app version

---

## ⭐ Show Your Support

Give a ⭐ if you like this project!  
Your support means a lot 💜

---

## 👨‍💻 Author

Developed By: **Sutanu Maity**

🎓 Full Stack Developer (MERN)

💡 Passionate about building interactive, user-friendly web applications

- 💻 GitHub: https://github.com/msutanu78
- 📧 Email: maitysutanu7@gmail.com
- 🌐 LinkedIn: https://www.linkedin.com/in/sutanu-maity-7979b723a

Built with curiosity, creativity, and a focus on user experience.

