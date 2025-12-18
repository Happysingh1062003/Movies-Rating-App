# 🎬 Movie Rating App

![Home Page](./public/image.png)

Movie Rating App is a modern movie discovery web application built using **React.js** and **Appwrite**.  
It allows users to search for movies, view essential details, and explore **top trending movies based on real user searches**.

The application focuses on speed, simplicity, and real-time trending insights powered by user activity.

---

## 🚀 Features

### 🔍 Search Movies
- Search movies instantly by title
- View key details such as:
  - Movie title
  - Release year
  - Rating
  - Poster & overview

### 📈 Trending Movies (User-Based)
- Displays top trending movies based on what users search
- Trending list updates dynamically
- Powered by Appwrite database analytics

### ⚡ Fast & Responsive UI
- Built with React.js for smooth performance
- Fully responsive for mobile and desktop
- Clean and minimal user interface

### ☁️ Backend with Appwrite
- Stores user search data
- Tracks movie popularity
- Generates real-time trending movies

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript (ES6+)
- HTML5
- CSS3

### Backend & APIs
- Appwrite (Database & API)
- TMDB API (The Movie Database) for fetching movie details

---

## 🔑 API Usage

- **TMDB API** is used to fetch:
  - Movie information
  - Ratings
  - Release dates
  - Posters and metadata

- **Appwrite** is used to:
  - Store user search queries
  - Track popularity
  - Generate trending movies dynamically

---

## 🧠 How Trending Works

1. User searches for a movie  
2. Search data is stored in Appwrite  
3. Movies with higher search frequency appear in Trending  
4. Trending list updates automatically  

---

## 📦 Installation & Setup

```bash
git clone https://github.com/Happysingh1062003/Movies-Rating-App.git
cd Movies-Rating-App
npm install
npm run dev
