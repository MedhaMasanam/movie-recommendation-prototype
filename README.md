<div align="center">
  
# 🎬 Movie Recommendation App

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)](https://expressjs.com/)

*A fast, modern full-stack movie recommendation prototype built with a React frontend and Node/Express backend.*

</div>

## 📌 Overview

This project is a lightweight, full-stack web application designed to recommend movies based on genre filtering. It demonstrates the ability to build a responsive frontend using **React (Vite)** and **Tailwind CSS**, seamlessly connected to a custom REST API powered by **Node.js** and **Express**.

## 🚀 Key Features

- **Dynamic UI:** Real-time movie filtering by genre with instant DOM updates.
- **RESTful API:** Custom Express server serving JSON datasets via standard HTTP GET requests.
- **Modern Build Tools:** Powered by Vite for lightning-fast HMR (Hot Module Replacement) and optimized production builds.
- **Responsive Design:** Fully styled with Tailwind CSS for a mobile-first, fluid user experience.
- **CORS Configured:** Secure cross-origin resource sharing implemented for seamless client-server communication.

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Frontend** | React 19, Vite, Tailwind CSS |
| **Backend** | Node.js, Express.js, CORS |
| **Data Layer** | Local JSON Store |

---

## 📂 Architecture & Structure

```text
movie-recomm/
├── server/                 # Express Backend API
│   └── index.js            # Main server entry point
├── src/                    # React Frontend
│   ├── components/         # Reusable UI components
│   │   ├── GenreSelector.jsx
│   │   └── MovieList.jsx
│   ├── data/               # Movie dataset
│   │   └── movies.json
│   ├── App.jsx             # Main application component
│   └── index.css           # Global Tailwind styles
```

---

## ⚙️ Local Development Setup

Ensure you have **Node.js (v18+)** and **npm** installed on your machine.

### 1. Start the Backend API (Terminal 1)
```bash
cd server
npm install express cors
node index.js
```
*The API will start at `http://localhost:3000/api/movies`*

### 2. Start the Frontend Application (Terminal 2)
```bash
# Return to the root directory
npm install
npm run dev
```
*The React app will start at `http://localhost:5173`*

---

## 🔌 API Endpoints

### `GET /api/movies`
Returns a JSON array containing the full movie dataset, including titles, genres, and metadata.

---

## 🧑‍💻 Developer

**Medha Masanam**
- GitHub: [@MedhaMasanam](https://github.com/MedhaMasanam)
- Portfolio: [MedhaMasanam.github.io](https://MedhaMasanam.github.io)

*If you found this repository helpful, please consider leaving a ⭐!*
