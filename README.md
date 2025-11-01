
# The Seventh Bazaar — MkDocs Material

Zero‑maintenance docs site for your party rules.

## Local preview
```bash
pip install mkdocs-material
mkdocs serve
```
Visit http://127.0.0.1:8000

## Deploy to GitHub Pages (auto)
1. Push this repo to GitHub.
2. In GitHub → Settings → Pages: set **Source** to **GitHub Actions**.
3. The included workflow will build and publish to **gh-pages** automatically.

## Manual deploy (optional)
```bash
pip install ghp-import
mkdocs build
ghp-import -n -p site
```
