# Movie Explorer – Discover Your Favorite Films

[https://new-movie-explorer.netlify.app/]

A modern, responsive React application that allows users to discover trending movies, search for specific films, view detailed information, and save favorites. This application integrates with The Movie Database (TMDb) API to provide real-time movie data.

---

## ✅ 1️⃣ Install prerequisites

Before starting, make sure you have:

- **Node.js** installed (LTS version, e.g., 18.x or 20.x)
- **npm** (comes with Node.js) or **yarn**
- **Git** installed

---

## 🎬 Features

- 🔐 **User Login:** Simple username/password login with credentials stored in localStorage.
- 🌟 **Trending Movies:** Display trending movies of the week from TMDb on the homepage.
- 🌟 **Search & Filters:** Search movies by title, filter by genre, release year, and minimum rating.
- 🎞️ **Movie Details:** View detailed info, including poster, trailer, cast, director, runtime, budget, and genres.
- ❤️ **Favorites:** Add/remove movies to a favorites list, persisted in localStorage.
- 💡 **Light/Dark Mode:** Toggle between light and dark themes, saved in localStorage.
- 📱 **Responsive Design:** Fully responsive layout for mobile, tablet, and desktop.
- 🛑 **Error Handling:** Graceful handling of API errors and invalid routes with a 404 page.
- 🔁 **Lazy Loading:** Pages are lazy-loaded to improve initial load performance.

---

## 🛠️ Technologies Used

- **React** (with Context API)
- **React Router**
- **Material UI**
- **Axios**
- **TMDb API**
- **Lucide React** (icons)

---

## 📦 Project Structure

```
src/
├── components/          # Reusable UI components
├── context/             # React Context for state management
├── pages/               # Page components
├── services/            # API integration
├── App.jsx              # Main app component and routing
└── index.js             # Application entry point
```

---

## ⚙️ Installation and Setup

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd movie-explorer
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Create environment variables**

   Create a `.env` file in the root directory:
   ```
   REACT_APP_TMDB_API_KEY=your_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

---

## 🔄 API Integration

This application uses the TMDb API to fetch movie data. You must provide your own TMDb API key in the `.env` file.

---

## 💾 State Management

The application uses React's Context API for global state (movies, favorites, filters, theme, etc.).

---

## 🔒 Authentication

Simple login system that stores the username in localStorage. (For demo purposes only.)

---

## 📱 Responsive Design

Mobile-first, responsive layout using Material UI.

---

## 🙏 Acknowledgments

- [The Movie Database (TMDb)](https://www.themoviedb.org/) for the API
- [Material-UI](https://mui.com/) for UI components
- [Lucide React](https://lucide.dev/) for icons

---

## 📄 License

This project is licensed under the MIT License.
