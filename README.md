# here-site

Public static site for **Here**, a small iOS app for noticing your attention.

- `index.html` — landing page
- `privacy/` — privacy policy (linked from App Store Connect)
- `styles.css` — design tokens mirrored from the app's design system

Served via GitHub Pages from the `main` branch root. The app's source code lives
in a separate private repository.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
