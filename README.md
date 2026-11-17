# Abhishek Khunt – Portfolio

Personal portfolio website of **Abhishek Khunt**, Senior Unity Game Developer.

Plain HTML, CSS and JavaScript – no build step. Open `index.html` or host the folder on GitHub Pages.

## Files

| File | What it is |
|---|---|
| `index.html` | All page content (text, games, links) |
| `style.css` | Design, colors and light/dark themes |
| `script.js` | Theme toggle, mobile menu, scroll animations |
| `assets/Abhishek_Khunt_CV.pdf` | CV for the "Download CV" button |
| `assets/icons/` | Game icons |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Host on GitHub Pages

1. Sign in to GitHub and create a **new public repository** named exactly
   `<your-github-username>.github.io` (for example `abhishekkhunt.github.io`).
2. On the new repository page, click **uploading an existing file**.
3. Drag **everything inside** this `portfolio` folder (not the folder itself) into the page:
   `index.html`, `style.css`, `script.js`, `README.md`, `.nojekyll` and the `assets` folder.
   *Tip: `.nojekyll` is a hidden file. If you cannot drag it, it is optional.*
4. Click **Commit changes**.
5. Go to **Settings → Pages**. Under *Build and deployment* choose
   **Source: Deploy from a branch**, **Branch: main**, folder **/ (root)**, then **Save**.
6. Wait 1–2 minutes. Your site will be live at
   `https://<your-github-username>.github.io`

If you name the repository something else (for example `portfolio`), the link becomes
`https://<your-github-username>.github.io/portfolio/`.

## Updating the site

- **New CV:** replace `assets/Abhishek_Khunt_CV.pdf` with the new file (keep the same name).
- **New game:** copy one `<article class="game">…</article>` block in `index.html`,
  change the name, text, links and icon, and put the icon in `assets/icons/`.
- Upload the changed files to the same repository; the site updates in about a minute.
