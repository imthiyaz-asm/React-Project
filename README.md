# Netflix Clone (React + Vite)

A simple Netflix-style UI: fixed navbar that darkens on scroll, a hero banner,
horizontally scrolling movie rows, and a demo watch page with routing.

## Stack
- React 18
- React Router v6
- Vite

## Run locally
```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # production build in /dist
npm run preview  # preview the build
```

## Structure
```
src/
  components/   Navbar, Hero, Row, MovieCard
  pages/        Home, Watch
  data/         movies.js  (sample catalog + helpers)
  styles/       index.css
  App.jsx       routes
  main.jsx      entry
```

## Make it real
- Swap `src/data/movies.js` for the TMDB API (https://developer.themoviedb.org).
- Replace the placeholder player in `pages/Watch.jsx` with a real `<video>` or embed.
- Poster images use picsum.photos placeholders — no API key needed.
