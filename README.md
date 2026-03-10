# AnimeWorld Website

[![HTML5](https://img.shields.io/badge/HTML5-Frontend-orange?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Styling-blue?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Static Site](https://img.shields.io/badge/Deployment-Static%20Site-green)](#deployment)
[![Netlify Status](https://api.netlify.com/api/v1/badges/63a04b05-ba8c-45e6-b721-51924f1068ec/deploy-status)](https://app.netlify.com/projects/agrimate-ai/deploys)

A clean, multi-page anime showcase built with pure HTML and CSS. It features a dark mode toggle, animated icon navigation, and rich card layouts for anime series and movies.

## Pages
- `index.html` — Home page with hero, Top 5 Anime, and Featured Movies
- `genres.html` — Genre-based anime collections
- `movies.html` — Anime movie collections

## Live Demo
`https://anime-world-1.netlify.app/`

## Features
- Dark mode toggle (persistent via `localStorage`)
- Animated icon navigation inside the navbar
- Responsive card grids with hover effects
- Theme tokens using CSS variables for easy color customization
- Smooth scrolling and modern layout

## Project Structure
```
.
├─ index.html
├─ genres.html
├─ movies.html
├─ style.css
├─ image.png
└─ README.md
```

## How To Use
1. Open `index.html` in any browser.
2. Navigate to `Genres` and `Movies` using the navbar.
3. Toggle dark mode using the moon/sun icon.

## Customization
- Colors and theme tokens: `style.css` under `:root` and dark mode overrides.
- Cards content: edit the `<article class="anime-card">` blocks in each HTML file.
- Images: replace the `img` URLs or `image.png` with your own.

## Notes
- No build tools required.
- Works fully offline except for web fonts and icon CDN.

## Credits
- Icons: Ionicons
- Fonts: Google Fonts (Poppins)
