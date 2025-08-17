# 📰 MERN Blog Platform

A full-stack **Blogging Platform** built with the **MERN stack (MongoDB, Express, React, Node.js)**.  
This is the **main repository** that organizes the project, with links to both frontend and backend.

## 🌐 Live Demo
- Frontend: [https://mern-blog-frontend.vercel.app](https://mern-blog-frontend.vercel.app)  
- Backend API: [https://mern-blog-backend.onrender.com](https://mern-blog-backend.onrender.com)

---

## 📂 Project Structure
- **frontend/** → React frontend ([Repo link](https://github.com/candy-arun/mern-blog-frontend))  
- **backend/** → Express + MongoDB backend ([Repo link](https://github.com/candy-arun/mern-blog-backend))

This repo uses **git submodules** to link both.

---

## ✨ Features
- 🔑 User authentication (Register/Login with JWT)  
- 📝 Create, edit, and delete blog posts  
- 🏷️ Tag support for blogs  
- 👀 View all blogs or a single blog in detail  
- ⏱️ Real-time timestamps  

---

## 🚀 Quick Start
Clone with submodules:
```bash
git clone --recurse-submodules https://github.com/candy-arun/mern-blog.git
cd mern-blog

Run backend

cd backend
npm install
npm start

Run frontend

cd ../frontend
npm install
npm start

🛠️ Tech Stack

Frontend: React, Axios, TailwindCSS

Backend: Node.js, Express, MongoDB, Mongoose, JWT

Deployment: Vercel (frontend), Render (backend)

📌 Future Enhancements

📸 Image upload for blogs

💬 Comments & Likes system

👤 User profile pages

🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.
