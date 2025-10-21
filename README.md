# Circuit Leg Day Training Manual (GitHub Pages)

Static site for a 30–40 minute circuit-style leg workout. This repository is ready to publish with GitHub Pages.

What's included

- `index.html` — The provided HTML for the training manual.
- `styles.css` — Lightweight responsive styles.
- `assets/` — Placeholder directory for exercise images (not included).

How to preview locally

1. Open this folder in VS Code. You can use the Live Server extension to preview, or use a simple Python HTTP server:

```powershell
# From the repository root
python -m http.server 8000
# Then open http://localhost:8000 in your browser
```

Publish on GitHub Pages

1. Create a new GitHub repository and push the code.
2. In your repo settings -> Pages, choose the `main` branch (or `gh-pages`) and root `/` as the folder. Save.
3. Your site will be available at `https://<username>.github.io/<repo>` (or at the repository's Pages domain).

Notes

- Add your images under `assets/img/` matching the filenames in `index.html`.
- Consider enabling `gh-pages` branch or the repository root for Pages based on your workflow.

License

Public domain or pick a license you prefer.
