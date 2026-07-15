# Portfolio

A single-file portfolio site (`index.html` — HTML, CSS and JS all in one place, no build step needed).

## 1. Customize it

Open `index.html` and search for `EDIT:` — every spot you should personalize is marked with that comment:
- Your name (hero heading)
- Email, LinkedIn, GitHub links (contact section + resume button)
- Work experience entries (duplicate a `.tl-item` block for more)
- Project cards (title, description, tags, live/code links)
- Rotating role titles in the status bar (bottom of the `<script>`)

## 2. Push it to GitHub

This folder is already a git repo with an initial commit. From inside this folder:

```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git branch -M main
git push -u origin main
```

Two naming options on GitHub:
- Repo named `portfolio` (or anything) → site will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`
- Repo named exactly `YOUR-USERNAME.github.io` → site will be live at `https://YOUR-USERNAME.github.io/` (root domain, no path)

## 3. Turn on GitHub Pages

In your new GitHub repo: **Settings → Pages → Source → Deploy from a branch → Branch: `main`, folder: `/ (root)` → Save**.

GitHub will give you the live URL within a minute or two. Any future `git push` updates the live site automatically.

## 4. Add a resume (optional)

Drop a `resume.pdf` into this folder, commit it, then point the "Resume" button in `index.html` at `resume.pdf` instead of `#`.
