# My Personal Website

Personal academic website hosted with GitHub Pages.

## Site structure

- `index.html` — homepage
- `style.css` — shared website styles
- `projects/index.html` — projects directory
- `projects/vesseltok/index.html` — VesselTok project page
- `assets/` — profile photo, CV, and other static files

## Local preview

From the repository root, run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Publishing

Publish the repository root from the `main` branch using GitHub Pages. Changes appear after the site is deployed.

The existing `assets/profile.png` and `assets/cv.pdf` should remain in the `assets` directory. Publication figures are currently referenced from public research repositories.
