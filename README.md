# Nabil Hakeem — Portfolio

Personal portfolio site for **Nabil Hakeem, Senior Product Manager**. Single-page, static HTML/CSS/JS — no build step, no dependencies.

## Structure

```
nabil-portfolio/
├── index.html      # the entire site (inline CSS + JS)
├── assets/         # product screenshots (360, Belvro, Convertedin, Rubikans)
└── README.md
```

## View locally

Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Publish on GitHub Pages

1. Create a **public** repo on GitHub (e.g. `nabil-portfolio` or `<username>.github.io`).
2. From this folder:
   ```bash
   git remote add origin https://github.com/<username>/<repo>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / `root` → Save**.
4. Your site goes live at `https://<username>.github.io/<repo>/` within a minute or two.

## Open items

- [ ] Replace the LinkedIn URL in the Contact section with the real profile (currently a best-guess placeholder).
- [ ] IMOX card has no product screenshots (Drive holds only strategy docs) — add screenshots or keep the "instrumentation-first" note.
- [ ] Confirm all 5 Google Docs case-study links are shared as "Anyone with the link · Viewer".

## Credits

Screenshots sourced from the owner's own product work (360 Company, Belvro Wealth, Convertedin, 4eShopping/Rubikans).
