# ▶ YouTube Clone — Landing Page

A pixel-accurate recreation of the YouTube homepage built with pure HTML and CSS. No JavaScript, no frameworks, no dependencies — just clean, handwritten markup and styling across four organised stylesheets.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![No JavaScript](https://img.shields.io/badge/JavaScript-none-lightgrey?style=flat)
![No dependencies](https://img.shields.io/badge/dependencies-none-brightgreen?style=flat)

---

## Preview

> _Add a screenshot here — e.g. `![Preview](./preview.png)`_

---

## Features

- **Header / Navbar** — YouTube logo, hamburger menu, search bar with search and voice-search buttons (with tooltips), upload icon, apps icon, notification bell with unread count badge, and user profile picture
- **Sidebar navigation** — icon + label links for Home, Explore, Subscriptions, Originals, YouTube Music, and Library
- **Video grid** — 6 video preview cards each with a thumbnail, video duration overlay, channel profile picture, video title, author name, and view count with upload date
- **CSS-only tooltips** — hover tooltips on the search, voice search, and upload buttons with no JavaScript
- **Roboto typeface** — loaded from Google Fonts to match YouTube's native typography

---

## Project Structure

```
youtube-clone/
├── index.html                  # Page structure and all content
├── styles/
│   ├── general.css             # Base resets and global styles
│   ├── header.css              # Navbar and top bar styles
│   ├── sidebar.css             # Sidebar navigation styles
│   └── video.css               # Video grid and card styles
├── icons/                      # SVG icons used throughout the UI
│   ├── hamburger-menu.svg
│   ├── youtube-logo.svg
│   ├── search.svg
│   ├── voice-search-icon.svg
│   ├── upload.svg
│   ├── youtube-apps.svg
│   ├── notifications.svg
│   ├── home.svg
│   ├── explore.svg
│   ├── subscriptions.svg
│   ├── originals.svg
│   ├── youtube-music.svg
│   └── library.svg
├── thumbnails/                 # Video thumbnail images (.webp)
│   ├── thumbnail-1.webp
│   ├── thumbnail-2.webp
│   ├── thumbnail-3.webp
│   ├── thumbnail-4.webp
│   ├── thumbnail-5.webp
│   └── thumbnail-6.webp
└── channel-pictures/           # Channel profile pictures
    ├── my-channel.jpeg
    ├── channel-1.jpeg
    ├── channel-2.jpeg
    ├── channel-3.jpeg
    ├── channel-4.jpeg
    ├── channel-5.jpeg
    └── channel-6.jpeg
```

---

## Getting Started

No installation or build step needed.

```bash
git clone https://github.com/your-username/youtube-clone.git
cd youtube-clone
open index.html
```

Or download the project folder and open `index.html` directly in any modern browser. Make sure the `styles/`, `icons/`, `thumbnails/`, and `channel-pictures/` folders stay in the same directory as `index.html` so all assets load correctly.

---

## Video Cards Included

| # | Title | Channel |
|---|-------|---------|
| 1 | Talking Tech and AI with Google CEO Sundar Pichai! | Marques Brownlee |
| 2 | Try Not To Laugh Challenge #9 | Markiplier |
| 3 | Crazy Tik Toks Taken Moments Before DISASTER | SSSniperWolf |
| 4 | The Simplest Math Problem No One Can Solve - Collatz Conjecture | Veritasium |
| 5 | Kadane's Algorithm to Maximum Sum Subarray Problem | CS Dojo |
| 6 | Anything You Can Fit In The Circle I'll Pay For | MrBeast |

---

## What I Learned

- Organising CSS across multiple focused stylesheets (`general`, `header`, `sidebar`, `video`) for clean separation of concerns
- Building a multi-region page layout (fixed header, sidebar, main content area) using CSS Flexbox and Grid
- Implementing CSS-only tooltips using `position: absolute` inside `position: relative` containers
- Replicating a complex, production-scale UI with high visual fidelity by carefully deconstructing a real-world interface
- Working with SVG icons and `.webp` image assets in a structured project folder

---

## Browser Support

Works in all modern browsers — Chrome, Firefox, Safari, and Edge.

---

## License

MIT — free to use, modify, and distribute.
