# Divine Dove Glow — Apostolic Fellowship Ministries

A pure static website for **Apostolic Fellowship Ministries Church, Bangalore**.  
Converted from React + Python to 100% static HTML, CSS & JavaScript.

## 📁 Project Structure

```
divine-dove-glow/
├── index.html        ← Home page (with intro video)
├── about.html        ← About the church
├── services.html     ← Service timings
├── gallery.html      ← Photo gallery with lightbox
├── contact.html      ← Contact form + map + prayer request
├── library.html      ← Full church library system
├── style.css         ← All styles (no frameworks)
├── script.js         ← Shared JS (navbar, theme, verse slider, etc.)
├── library.js        ← Library-specific JS (book management)
└── assets/
    ├── logo.png
    ├── hero-bg.jpg
    ├── baptism.jpg
    ├── bible.jpg
    ├── congregation.jpg
    ├── pastor.jpg
    ├── prayer.jpg
    ├── revival.jpg
    ├── study.jpg
    ├── worship-1.jpg
    └── media/
        └── intro.mp4
```

## 🚀 Getting Started

Simply open `index.html` in your browser — no build step required.

## 🌐 Deploy on Netlify / GitHub Pages

1. Push this folder to a GitHub repository.
2. On **Netlify**: New site → Import from GitHub → select repo → Deploy.
3. On **GitHub Pages**: Settings → Pages → Source: `main` branch → `/` (root) → Save.

No build command or publish directory needed — it's all static files.

## ✨ Features

- **Intro video** — plays once per session, skippable
- **Dark / Light mode** — persisted via localStorage
- **Verse slider** — auto-rotates Bible verses
- **Gallery lightbox** — click any photo to enlarge
- **Floating prayer button** — available on every page
- **Church Library** — browse 48+ seed books, borrow system with admin panel
  - LocalStorage persistence
  - CSV/Excel upload (CSV format)
  - Admin PIN: `afm2025`
  - Add / remove / toggle availability of books
- **Contact forms** — contact form + prayer request form
- **Embedded Google Map** — church location
- **Fully responsive** — mobile-first design
- **Bootstrap Icons** — loaded via CDN
- **Google Fonts** — Cormorant Garamond + Inter

## 📱 Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero, about preview, services, verse slider, testimonials, sermons |
| About | `about.html` | Beliefs, ministries, pastors, stats |
| Services | `services.html` | All service timings |
| Gallery | `gallery.html` | Masonry photo grid with lightbox |
| Contact | `contact.html` | Map, contact form, prayer form, service times |
| Library | `library.html` | Full book management system |

## 🎨 Theme Colors

- **Royal**: `#3730a3` (deep indigo)
- **Gold**: `#c9a84c` (warm gold)
- **Royal Deep**: `#1e1b4b` (dark navy)

---

*Maranatha! Lord Jesus Come Soon 🙏*
