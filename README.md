# resume

My online resume, built with plain HTML and CSS and hosted on GitHub Pages.

Live site: https://dileep892.github.io/resume/

## Update content

- Text and links: edit `index.html`.
- Resume PDF: replace `Dileep-Velma-Network-Lead.pdf` (keep the filename, or update the two links in `index.html`).
- Photo: replace `profile.jpg`.
- Colors: change the `:root` variables at the top of `styles.css`.

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Publish on GitHub Pages 

1. Create a **public** repo named `resume` under your account (`dileep892`).
2. Push this folder to the `main` branch.
3. Repo **Settings > Pages > Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`.
4. Wait a minute, then open `https://dileep892.github.io/resume/`.

To use `https://dileep892.github.io/` as the address instead, name the repo `dileep892.github.io`.
