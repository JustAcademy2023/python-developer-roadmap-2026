# 🐍 Python Developer Roadmap 2026 — Trail Map Landing Page

> Skills, Projects and Career Opportunities — mapped out like a real trail, checkpoint by checkpoint.

A single-page, dependency-free landing page that turns the "Python Developer Roadmap 2026" into a scroll-stopping, topographic **trail map** — instead of another generic dark-mode dev page. Built with plain HTML/CSS/JS so it deploys instantly on **GitHub Pages**, no build step required.

**🔗 Live concept sections:** Roadmap · Skills · Projects · Careers · Guide Services (Courses) · Field Notes (Blog)

---

## ✨ Highlights

- 🗺️ **Trail-map design system** — parchment palette, pine/lake/marker accent colors, dashed trail line, and topographic contour textures instead of the usual dark hero + gradient template.
- 🧭 **5-checkpoint roadmap** — Basecamp → Ridge Line → Mountain Pass → Summit Camp → Summit, each mapped to real skills and timeframes.
- 🃏 **Modern, hover-animated cards** for skills, projects, career routes, and courses.
- 📱 **Fully responsive** — clean breakpoints down to mobile, with a slide-out mobile menu.
- 🎬 **Scroll-reveal animations** via `IntersectionObserver` — no external animation library.
- 🔗 **Fully clickable, real links** to every course, bootcamp, and blog resource — all open safely in a new tab (`target="_blank" rel="noopener"`).
- ⚡ **Zero dependencies** — no npm, no build tools. Just open `index.html`.

---

## 📁 Project Structure

```
python-developer-roadmap-2026/
├── index.html      # Full landing page (HTML + CSS + JS, single file)
└── README.md        # You're reading it
```

---

## 🚀 Getting Started

### View it locally
Just open the file in your browser — no server needed:

```bash
git clone https://github.com/<your-username>/python-developer-roadmap-2026.git
cd python-developer-roadmap-2026
open index.html   # macOS
# or start index.html   (Windows)
# or xdg-open index.html   (Linux)
```

### Deploy on GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — your landing page will be live at:
   `https://<your-username>.github.io/python-developer-roadmap-2026/`

---

## 🔗 Resource Links Featured on the Page

| Section | Resource | Link |
|---|---|---|
| Guide Services | Python Training in Mumbai | https://www.justacademy.co/course-detail/mumbai/python-training-in-mumbai |
| Guide Services | Data Analytics Bootcamp in Mumbai | https://www.justacademy.co/job-bootcamp-detail/mumbai/data-analytics-bootcamp-in-mumbai-classroom-training-with-real-world-projects |
| Guide Services | MERN Stack Developer Bootcamp in Mumbai | https://www.justacademy.co/job-bootcamp-detail/mumbai/mern-stack-developer-bootcamp-in-mumbai-full-stack-web-development-classroom-training |
| Guide Services | Microsoft Power BI Training in Mumbai | https://www.justacademy.co/course-detail/mumbai/microsoft-power-bi-training-in-mumbai |
| Guide Services | Selenium Training in Mumbai | https://www.justacademy.co/course-detail/mumbai/selenium-training-in-mumbai |
| Guide Services | JavaScript Training in Mumbai | https://www.justacademy.co/course-detail/mumbai/javascript-training-in-mumbai |
| Field Notes | Python Institute Blog | https://www.justacademy.co/blog-detail/python-institute |

---

## 🛠️ Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, CSS Grid & Flexbox, no framework
- **Vanilla JavaScript** — mobile nav toggle + scroll-reveal via `IntersectionObserver`
- **Fonts** — Fraunces (display), IBM Plex Sans (body), IBM Plex Mono (data/labels) via Google Fonts

---

## 🎨 Design Notes

The page reframes a "developer roadmap" literally as a **hiking trail map**: an SVG dashed route with waypoint markers in the hero, numbered "checkpoints" down the roadmap section (justified here since the roadmap really is sequential), a parchment/paper color system, and topographic contour-ring textures — aiming for something that looks unmistakably different from the usual dark-terminal or cream-and-terracotta AI-generated template.

Feel free to swap the palette in `:root` at the top of `index.html` to restyle the whole page in one place.

---

## 📄 License

Free to use, modify, and deploy for personal or educational purposes.

---

<p align="center">Built for anyone starting the climb into Python development. 🐍🏔️</p>
