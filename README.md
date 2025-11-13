# Streamsense

Streamsense is a lightweight React web app for discovering movies and where to stream them. It integrates with public APIs (TMDB, OMDb, YouTube, Watchmode) to provide movie browsing, details, trailers, streaming availability, recommendations, and user favorites.

**[https://Ayush-Chechi.github.io/Streamsense](https://Ayush-Chechi.github.io/Streamsense)**

---

## Screenshots

![Homepage](Images/homepage.png)

![Movie details](Images/movie%20detail.png)

---

## Key Features

- Browse popular and trending movies
- Search movies and view detailed information (cast, synopsis, images)
- Watch trailers and related videos (YouTube embeds)
- Find streaming platforms where a movie is available (Watchmode integrations)
- Save favorites and view recommendations
- Light/Dark theme toggle

---

## Tech Stack

- UI: React, Vite
- Routing: React Router
- Styling: plain CSS (project src/css/)
- APIs: The Movie Database (TMDB), OMDb, YouTube Data API, Watchmode
- Deployment: GitHub Pages (via gh-pages)

---

## Project structure (top-level)

```
Streamsense/
├── public/                  # static assets/screenshots
├── src/
│   ├── components/          # React components
│   ├── pages/               # route pages (Home, MovieDetails, Favorites...)
│   ├── services/            # API helpers (api.js)
│   └── css/                 # styles
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

---

## Quick Start

### Requirements

- **Node.js** (version 18 or higher)
- **npm** (comes with Node.js)

### Steps

1. **Clone or navigate to the project folder** (if not already there):
   ```powershell
   cd C:\Users\ayush\Desktop\Projects\Streamsense
   ```

2. **Install dependencies**:
   ```powershell
   npm install
   ```

3. **Start the development server**:
   ```powershell
   npm run dev
   ```

4. **Open in your browser**:
   ```
   http://localhost:5173/Streamsense/
   ```

The site will reload automatically when you make changes!

---

## Contributing & License

Contributions welcome. Educational use only.
