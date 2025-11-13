# Streamsense

Streamsense is a lightweight React web app for discovering movies and where to stream them. It integrates with public APIs (TMDB, OMDb, YouTube, Watchmode) to provide movie browsing, details, trailers, streaming availability, recommendations, and user favorites.


[Live Demo](https://Ayush-Chechi.github.io/Streamsense) • [Actions](https://github.com/Ayush-Chechi/Streamsense/actions)



---

## Screenshots

Add screenshots to `public/screenshots/` and reference them here. Example markdown (replace filenames with your screenshots):

```markdown
![Homepage](public/screenshots/homepage.png)
![Movie details](public/screenshots/movie-details.png)
```


---


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

## Quick start

Requirements: Node.js (18+) and npm

```powershell
cd C:\Users\ayush\Desktop\Projects\Streamsense
npm install
npm run dev
```

Open: `http://localhost:5173/Streamsense/`


---

## Contributing & License

Contributions welcome. Educational use only.
"""

