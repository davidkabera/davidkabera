# Portfolio — David Kabera Kirwa

Static site. `index.html` is the portfolio landing page, `cv.html` is the full CV.

## Deploy to GitHub Pages

1. Create a public repo named `<your-username>.github.io` (e.g. `davidkirwa.github.io`).
   Using this exact name gives you `https://<your-username>.github.io/` with no subpath.

2. From this folder:

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
git push -u origin main
```

3. On GitHub: **Settings → Pages → Build and deployment**
   - Source: *Deploy from a branch*
   - Branch: `main`, folder: `/ (root)` → **Save**

4. Wait ~1 minute. The site goes live at `https://<your-username>.github.io/`.

## Notes

- If you use a differently-named repo instead (e.g. `portfolio`), the URL becomes
  `https://<your-username>.github.io/portfolio/`. All links here are relative, so both work.
- To update: edit, `git commit`, `git push`. Pages redeploys automatically.
