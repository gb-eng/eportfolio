# Portfolio Site

A single-page portfolio: dark background, warm beige, Bebas Neue + JetBrains
Mono, diagonal hazard-stripe dividers.

## 1. Fill in your details

Open `index.html` and replace every bracketed placeholder:

- `[YOUR NAME]` — appears in the `<title>`, hero, and footer
- `[YOUREMAIL@EXAMPLE.COM]` and the matching `mailto:` link in the Contact section
- `https://github.com/yourhandle`, `https://linkedin.com/in/yourhandle`, and the art/commissions link
- Each project's `#` links (Live demo / Source / Case study / Gallery)
- The three `<div class="project-media">` boxes — swap these for real `<img>` screenshots once you have them. Example:
  ```html
  <div class="project-media">
    <img src="images/project-1.png" alt="Screenshot of the code-switching learning app">
  </div>
  ```
  (drop your images in an `images/` folder next to `index.html`)

## 2. Preview locally

Just open `index.html` in a browser — no build step, no server required.

## 3. Deploy to GitHub Pages

1. Create a new GitHub repo (public), e.g. `yourhandle.github.io` for a
   root-domain site, or any name for a project site.
2. Push these three files (`index.html`, `style.css`, `script.js`) — plus an
   `images/` folder if you added screenshots — to the repo's `main` branch.
   ```bash
   git init
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/yourhandle/your-repo.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Source** → select
   **Deploy from a branch** → branch **main**, folder **/ (root)** → Save.
4. Your site goes live in a minute or two at:
   - `https://yourhandle.github.io/` (if the repo is named `yourhandle.github.io`), or
   - `https://yourhandle.github.io/your-repo/` (any other repo name)

That's it — no build tooling, so every push to `main` updates the live site
automatically.
