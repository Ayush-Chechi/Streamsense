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

```
Streamsense/
├── public/                  # static assets
├── src/
│   ├── components/          # React components (NavBar, MovieCard, etc.)
│   ├── pages/               # route pages (Home, MovieDetails, Favorites...)
│   ├── services/            # API helpers (api.js)
│   └── css/                 # styles
├── .github/workflows/       # CI workflow (deploy to GitHub Pages)
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

Getting started (local development)

Requirements

- Node.js (18+) and npm

Install dependencies and run the dev server

```powershell
cd C:\Users\ayush\Desktop\Projects\Streamsense
npm install
npm run dev
```

Open the app in your browser at:

```
http://localhost:5173/Streamsense/
```

Notes about routing and base path

- The app is configured with `vite.config.js` `base: '/Streamsense/'` and `BrowserRouter` has `basename="/Streamsense"`. This ensures routes work correctly when the site is served from `https://<user>.github.io/Streamsense`.

Build for production

```powershell
npm run build
```

Deploying

Option A — GitHub Actions (recommended)

- This repository includes a workflow `.github/workflows/deploy.yml` which builds the site and deploys the `dist` folder to GitHub Pages on push to `main`.
- Make sure your repository is pushed to `https://github.com/Ayush-Chechi/Streamsense` and push your changes to `main`. GitHub Actions will run automatically and publish the site to:

```
https://Ayush-Chechi.github.io/Streamsense
```

Option B — Publish with `gh-pages` (one-off or local publish)

```powershell
npm install
npm run build
npx gh-pages -d dist
```

This will create and push a `gh-pages` branch and publish the `dist` folder to GitHub Pages.

Troubleshooting

- If you see a 404 on the GitHub Pages URL, check the repository Pages settings and the Actions workflow run logs:
	- Actions: `https://github.com/Ayush-Chechi/Streamsense/actions`
	- Pages: `https://github.com/Ayush-Chechi/Streamsense/settings/pages`
- If `npm ci` fails in CI because `package-lock.json` is out of sync, run `npm install` locally and commit the updated `package-lock.json`.

Contributing

- Contributions are welcome. Open issues or pull requests.

License

This project is provided for educational purposes. See the repository license (if any) or contact the author for reuse permissions.

