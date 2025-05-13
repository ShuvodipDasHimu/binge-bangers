# 🎬 Binge Bangers

**Binge Bangers** is a fast and minimal movie discovery app that lets users **search for movies** and explore **trending titles** based on the most searched movies. Built with React + Vite, powered by TMDB API for movie data and Appwrite for tracking search popularity.

![Binge Bangers Screenshot](./public/screenshot.png)

---

## 🚀 Live Demo

👉 [binge-bangers.vercel.app](https://binge-bangers.vercel.app/)

---

## 📌 Features

- 🔍 **Instant Movie Search** with debounce functionality
- 🔥 **Trending Section** showing most searched movies by users
- 🎨 Clean and responsive UI with Tailwind CSS
- 📈 **Appwrite Integration** to log and update search statistics
- ⚡ Blazing fast using Vite and modern React hooks

---

## 🛠️ Tech Stack

- **Frontend**: React, Vite, Tailwind CSS
- **API**: [TMDB API](https://www.themoviedb.org/documentation/api)
- **Database**: [Appwrite](https://appwrite.io)
- **Deployment**: [Vercel](https://vercel.com)

---

## 🧠 How It Works

1. User types a movie name → debounced search triggers TMDB API.
2. The first result is sent to Appwrite to track how many times it was searched.
3. Trending section dynamically shows the most searched movies with poster thumbnails.