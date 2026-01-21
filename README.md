# Dev Detective

A lightweight web app that looks up any GitHub username and presents their public profile with stats, links, and a sleek dark/light theme. Built with vanilla HTML, CSS, and JavaScript using the GitHub Users API.

## 🌐 Live Demo
- https://devdetective121.netlify.app/

## 🚀 Features
- GitHub profile lookup with avatar, bio, repos, followers, following, location, website, Twitter, and company links.
- Dark/light theme toggle with preference persisted in `localStorage`.
- Responsive layout tuned for mobile, tablet, and desktop breakpoints.
- Inline error state for unknown users and graceful handling for missing profile fields.
- Default view preloaded with `SHREENATH72` on initial load.

## 🛠️ Tech Stack
- HTML5 for the single-page layout.
- CSS3 (custom properties, flexbox, responsive media queries).
- Vanilla JavaScript for API calls, rendering, and theme switching.
- GitHub Users REST API for live profile data.

## 📦 Project Structure
- `index.html` — markup and root container.
- `styles.css` — theming, layout, and responsive rules.
- `script.js` — API fetch, render logic, and theme persistence.
- `assets/` — icons and PWA manifest assets.


## 🌙 Theme Toggle
- Click the mode switch in the header to toggle dark/light.
- Preference is stored in `localStorage` (`dark-mode` key) and restored on reload.

## 🔗 API
- Uses `https://api.github.com/users/{username}` to fetch public profile data.
- Handles `Not Found` responses with an inline “no search results” message.

## 📱 Responsive Notes
- Mobile-first layout with enhanced spacing on tablets (`>=768px`) and repositioned avatar/content on desktop (`>=1280px`).

## 🤝 Contributing
Feel free to open issues or pull requests for improvements or bug fixes.

## 📄 License
This project is open source and available for personal and commercial use.
