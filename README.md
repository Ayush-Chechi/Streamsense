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

```
http://localhost:5173/Streamsense/
```

---

## Build & Deploy

Build for production:

```powershell
npm run build
```

Option A — GitHub Actions (recommended)

- The repository contains `.github/workflows/deploy.yml`. Push to `main` and Actions will build and publish to GitHub Pages at:

```
https://Ayush-Chechi.github.io/Streamsense
```

Option B — Manual publish with `gh-pages`:

```powershell
npm install
npm run build
npx gh-pages -d dist
```

---

## Notes & Troubleshooting

- If Pages shows a 404, check:
  - Actions logs: `https://github.com/Ayush-Chechi/Streamsense/actions`
  - Pages settings: `https://github.com/Ayush-Chechi/Streamsense/settings/pages`
- If CI fails on `npm ci`, run `npm install` locally and commit the updated `package-lock.json`.

---

## Contributing

- Contributions welcome — open issues or PRs.

---

## License

This project is provided for educational purposes. See repository license or contact the author for reuse permissions.

