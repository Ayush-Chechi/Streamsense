# Streamsense

Streamsense is a lightweight React web app for discovering movies and where to stream them. It integrates with public APIs (TMDB, OMDb, YouTube, Watchmode) to provide movie browsing, details, trailers, streaming availability, recommendations, and user favorites.

**Demo:** `https://Ayush-Chechi.github.io/Streamsense`

**Key Features**

- Browse popular and trending movies
- Search movies and view detailed information (cast, synopsis, images)
- Watch trailers and related videos (YouTube embeds)
- Find streaming platforms where a movie is available (Watchmode integrations)
- Save favorites and view recommendations
- Light/Dark theme toggle

**Tech Stack**

- UI: React, Vite
- Routing: React Router
- Styling: plain CSS (project `src/css/`)
- APIs: The Movie Database (TMDB), OMDb, YouTube Data API, Watchmode
- Deployment: GitHub Pages (via `gh-pages`) or GitHub Actions

Project structure (top-level)
# Streamsense

[Live Demo](https://Ayush-Chechi.github.io/Streamsense) • [Actions](https://github.com/Ayush-Chechi/Streamsense/actions)

---

Streamsense is a modern, lightweight React app for discovering movies and where to stream them. It integrates with public APIs (TMDB, OMDb, YouTube, Watchmode) to show movie details, trailers, streaming availability, and personalized recommendations.

<!-- badges -->
![GitHub Pages](https://img.shields.io/badge/pages-deployed-brightgreen)
![Vite](https://img.shields.io/badge/bundler-vite-blue)
![React](https://img.shields.io/badge/framework-react-61dafb)

---

## Demo

Open the app in your browser:

[https://Ayush-Chechi.github.io/Streamsense](https://Ayush-Chechi.github.io/Streamsense)

> If the demo shows a 404, the site may still be building — check the Actions tab or Pages settings in the repository.

---

## Screenshots

Add screenshots to `public/screenshots/` and reference them here. Example markdown (replace filenames with your screenshots):

```markdown
![Homepage](public/screenshots/homepage.png)
![Movie details](public/screenshots/movie-details.png)
```

Placeholders (add your images to `public/screenshots/`):

![Homepage placeholder](public/screenshots/homepage.png)
![Details placeholder](public/screenshots/movie-details.png)

---

## Key Features

- Browse popular and trending movies
- Search movies and view details (cast, synopsis, images)
- Watch trailers (YouTube embeds)
- Find streaming platforms (Watchmode)
- Save favorites and get recommendations
- Light / Dark theme toggle

---

## Tech Stack

- React + Vite
- React Router
- Plain CSS (in `src/css/`)
- TMDB, OMDb, YouTube Data API, Watchmode
- Deployment: GitHub Pages (via Actions or `gh-pages`)

---

## Project structure (top-level)

```
Streamsense/
├── public/                  # static assets (put screenshots in public/screenshots/)
├── src/
│   ├── components/          # React components
│   ├── pages/               # route pages (Home, MovieDetails, Favorites...)
│   ├── services/            # API helpers (api.js)
│   └── css/                 # styles
├── .github/workflows/       # CI workflow (deploy to GitHub Pages)
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

---

## Quick start (development)

Requirements

- Node.js (18+) and npm

Run locally

```powershell
cd C:\Users\ayush\Desktop\Projects\Streamsense
npm install
npm run dev
```

Open:
"""
# Streamsense

[Live Demo](https://Ayush-Chechi.github.io/Streamsense) • [Actions](https://github.com/Ayush-Chechi/Streamsense/actions)

A concise React app to discover movies and where to stream them.

---

## Demo

https://Ayush-Chechi.github.io/Streamsense

*(If you see a 404 shortly after pushing, the site may still be building — check Actions.)*

---

## Screenshots

Current image files in your project (used below):

- Homepage: `Images/homepage.png`
- Movie details: `Images/movie detail.png`

Embed in markdown (example):

```markdown
![Homepage](Images/homepage.png)
![Movie details](Images/movie%20detail.png)
```

Rendered below (these will show if the files exist in the repo):

![Homepage](Images/homepage.png)
![Movie details](Images/movie%20detail.png)

If you prefer these images inside `public/screenshots/` (cleaner URLs), I can move and rename them.

---

## Features (short)

- Browse & search movies
- View details, trailers and streaming options
- Save favorites and get recommendations
- Light / Dark mode

---

## Quick start

Requirements: Node.js (18+) and npm

```powershell
cd C:\Users\ayush\Desktop\Projects\Streamsense
npm install
npm run dev
```

Open: `http://localhost:5173/Streamsense/`

---

## Build & Deploy

Build:

```powershell
npm run build
```

Deploy: GitHub Actions will build & publish to `https://Ayush-Chechi.github.io/Streamsense` on push to `main`.

Or publish locally with `gh-pages`:

```powershell
npx gh-pages -d dist
```

---

## Notes

- If CI fails on `npm ci`, run `npm install` locally and commit `package-lock.json`.
- The app uses `vite.config.js` `base: '/Streamsense/'` and `BrowserRouter` `basename="/Streamsense"` so routes work on GitHub Pages.

---

## Contributing & License

Contributions welcome. Educational use only.
"""

