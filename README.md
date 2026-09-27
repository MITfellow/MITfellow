# Simple GitHub Page + Profile

Light, minimal single-page site. No build step.

Files:
- `index.html` — the site
- `styles.css` — light styling
- `profile-README.md` — copy-paste template for your GitHub profile README
- `.nojekyll` — lets GitHub Pages serve files as-is

## Preview locally
Double-click `index.html`, or run:
```powershell
cd "C:\Users\DELL\Desktop\New folder (35)"
python -m http.server 8000
# open http://localhost:8000
```

## Put it on GitHub Pages (5 min)
1. Create repo named `YOUR-USERNAME.github.io`
2. Upload `index.html`, `styles.css`, `.nojekyll` to repo root
3. Go to repo Settings → Pages → Deploy from branch → `main` / `(root)` → Save
4. Visit `https://YOUR-USERNAME.github.io`

## Make your profile README show up
1. Create a **new** repo named exactly `YOUR-USERNAME` (same as username)
2. Add a `README.md` file, paste contents of `profile-README.md`
3. Commit — it appears on top of your github.com/YOUR-USERNAME page

## Customize
Search for `YOUR-USERNAME`, `Your Name`, `you@example.com` and replace.
Edit the 3 cards in `index.html` → `What we're building`.
