✨ Streamify — Real-Time Chat & Video Calling App 🚀
<p align="center"> <b>A full-stack real-time messaging + video calling platform built using Stream, MERN, and modern React tooling.</b> </p> <p align="center"> 💬 Real-Time Chat • 🎥 Video Calls • 🔐 JWT Auth • 🎨 32 Themes • ⚡ Scalable Architecture </p>

Demo App->
Login Page ->
<img width="1912" height="966" alt="image" src="https://github.com/user-attachments/assets/6105077b-fd76-480c-ba0b-d7026d79e63b" />

Dashboard Page ->
<img width="1913" height="961" alt="image" src="https://github.com/user-attachments/assets/e7015acb-c414-43c2-9892-6d900cf9b1d6" />

Chat Page ->
<img width="1918" height="868" alt="image" src="https://github.com/user-attachments/assets/42281274-0a0e-4827-bdb0-74e422629e57" />

Call Page ->
<img width="1917" height="870" alt="image" src="https://github.com/user-attachments/assets/ab749c8e-3003-4d3d-b629-cca2e9903589" />




🌟 Highlights

✅ Real-time messaging with typing indicators & reactions
✅ 1-on-1 & group video calls (screen sharing + recording support)
✅ JWT authentication with protected routes
✅ Language exchange platform UI with 32 unique themes
✅ Fully responsive UI (Desktop + Mobile)
✅ Built using scalable Stream Chat & Video SDK
✅ Zustand for global state + TanStack Query for API caching
✅ Clean backend architecture with Express + MongoDB
✅ Centralized error handling (Frontend + Backend)

🛠️ Tech Stack
✅ Frontend

React (Vite)

TailwindCSS + DaisyUI

TanStack React Query

Zustand

Axios

Stream Chat React UI (stream-chat-react)

Stream Video SDK (@stream-io/video-react-sdk)

React Router

✅ Backend

Node.js + Express

MongoDB + Mongoose

JWT Authentication

bcryptjs

cookie-parser

dotenv

cors

Stream Chat SDK (stream-chat)

---

```
streamify/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── lib/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── server.js
│   ├── .env.example
│   ├── package.json
│   └── package-lock.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── .env.example
│   ├── index.html
│   ├── eslint.config.js
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   ├── vite.config.js
│   ├── package.json
│   └── package-lock.json
│
├── .gitignore
└── README.md

```

## 🧪 .env Setup

### Backend (`/backend`)

```
PORT=5001
MONGO_URI=your_mongo_uri
STEAM_API_KEY=your_steam_api_key
STEAM_API_SECRET=your_steam_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

### Frontend (`/frontend`)

```
VITE_STREAM_API_KEY=your_stream_api_key
```

---

## 🔧 Run the Backend

```bash
cd backend
npm install
npm run dev
```

## 💻 Run the Frontend

```bash
cd frontend
npm install
npm run dev
```

💡 Main Features (Detailed)
💬 Chat System

Real-time messaging powered by Stream Chat

Typing indicators

Emoji reactions

1-on-1 and group chats

🎥 Video Calling

Stream Video SDK integration

1-on-1 and group calls

Screen sharing support

Recording support

🔐 Authentication

Secure JWT login/register

Protected routes

Proper backend validation & middleware handling

🎨 Themes + UI

32 UI themes (DaisyUI themes)

Responsive layout for all screens

Clean modern design

🧠 What Makes This Project Interview-Ready?

✅ Real-time communication engineering using Stream
✅ Clean folder separation (controllers/routes/models/middleware)
✅ Proper API handling + caching with TanStack Query
✅ Authentication security practices with JWT
✅ Scalable full-stack architecture (MERN)
✅ Production-ready frontend with Vite + Tailwind

📌 Future Improvements

✅ Media sharing (images/videos/docs)

✅ User profile & settings page

✅ Notifications and online/offline presence

✅ Chat search + pinned messages

✅ Deployment guides (Docker + CI/CD)

👨‍💻 Author

Bambam Kumar Gupta
🎓 B.Tech — MNNIT Allahabad
💻 Full-Stack Developer (MERN + React)

📌 LinkedIn: https://www.linkedin.com/in/bambam-gupta-773519266/
📌 GitHub: https://github.com/bambamHub

⭐ Support

If you liked this project, please give it a ⭐ on GitHub — it helps a lot! 💙
