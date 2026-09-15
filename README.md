# Gulian Ibrahim — Developer Portfolio

[![Live Site](https://img.shields.io/badge/Live_Site-GitHub_Pages-00FFD1?style=flat-square)](https://agcat80.github.io/portfolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gulian_Ibrahim-8B5CF6?style=flat-square)](https://www.linkedin.com/in/gulian-ibrahim-313a03261/)
[![GitHub](https://img.shields.io/badge/GitHub-AgCat80-white?style=flat-square)](https://github.com/AgCat80)

A sci-fi / cyber-tech themed developer portfolio built with vanilla HTML, CSS and JavaScript. No build tools, no frameworks — just a single `index.html` deployed to GitHub Pages.

## Live Demo

> [https://agcat80.github.io/portfolio](https://agcat80.github.io/portfolio-website)

## Features

- Animated particle data-stream canvas background
- Terminal boot sequence on page load
- Interactive skill node graph (canvas API)
- Data pipeline flow visualiser
- Project terminal-window cards
- Experience timeline
- Hackathon achievement badge
- Contact terminal pane
- CRT scanline overlay
- Fully responsive down to mobile
- Respects `prefers-reduced-motion`

## Tech Stack

| Layer | Choice |
|-------|--------|
| Markup | HTML5 |
| Styling | CSS3 custom properties, no framework |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | Space Mono + Inter via Google Fonts |
| Hosting | GitHub Pages |

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings > Pages**
3. Set source to `main` branch, root folder
4. GitHub Pages will publish at `https://<your-username>.github.io/<repo-name>`

## Local Preview

No build step needed:

```bash
git clone https://github.com/AgCat80/portfolio-website.git
cd portfolio
# open index.html in your browser, or use a simple server:
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Customisation

All personal data is inline in `index.html`. To update:

- **Projects**: edit the `.proj-terminal` blocks in the Projects section
- **Skills**: edit the `skills` array in the `<script>` tag
- **Timeline**: edit the `.tl-item` blocks in the Experience section
- **Boot sequence**: edit the `lines` array in the boot terminal script
- **Colours**: change CSS custom properties in `:root`

## Author

**Gulian Ibrahim** — Cape Town, South Africa  
BSc Computing @ STADIO | Former Head of IT @ Legates Group  
[ibrahimgulian404@gmail.com](mailto:ibrahimgulian404@gmail.com)
