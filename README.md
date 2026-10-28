# Luca-CS.github.io

Source of my personal site: <https://luca-cs.github.io>.

Plain HTML and CSS, no build step, no dependency, no tracker. The only JavaScript is a few lines for the light/dark button and for stopping the demo videos when the visitor asks for reduced motion. GitHub Pages serves the `main` branch as is.

| File | Role |
|---|---|
| `index.html` | The whole site: experience, projects, education, skills, contact |
| `assets/css/style.css` | Styles: light and dark themes, following the system until the visitor picks one |
| `404.html` | Page shown for unknown addresses |
| `cv.pdf` | CV, web version without phone number |
| `favicon.svg`, `assets/img/` | Icons and link preview image |
| `assets/demo/` | Screen recordings of Disk Manager and WikiMasters Tagger (WebM, MP4 fallback, poster), made on fake data |

Local preview:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.
