# Trello-like Task Board (MERN)

A simple drag-and-drop task management board inspired by Trello.

## 🔧 Features

- Create, edit, delete tasks
- Move tasks across columns
- Three columns: To Do, In Progress, Done
- MongoDB backend with Express and React frontend
- Deployed on Render + Vercel

## 🛠 Tech Stack

- Frontend: React + Vite + Tailwind CSS
- Backend: Express.js, MongoDB, Mongoose
- Drag and Drop: react-beautiful-dnd

## 🚀 Deployment

- Frontend: Vercel
- Backend: Render
- Database: MongoDB Atlas

## 📦 Environment Variables

Backend (`server/.env`):

```
MONGO_URI=mongodb://localhost:27017/taskboard
PORT=5000
```

Frontend (`client/.env`):

```
VITE_API_BASE_URL=http://localhost:5000/api/tasks

## 📁 How to Run

```bash
# Backend
cd server
npm install
npm run dev

# Frontend
cd client
npm install
npm run dev
```
