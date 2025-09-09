# Web Slate (Scene / Cut / Take)

A simple web-based clapperboard slate.

## Features
- Dark theme, high-contrast lines
- Fields: SCENE, CUT, TAKE (1–100, wrap-around)
- Scroll to change numbers (Shift: ±10)
- Touch drag up/down to increment/decrement
- Keyboard controls (↑/↓ ±1, PageUp/PageDown ±10, Home/End min/max)

## How to deploy to GitHub Pages
1. Create a new repo on GitHub.
2. Add these files and push:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin <YOUR_REPO_URL>
   git push -u origin main
   ```
3. Enable Pages in repo Settings → Pages → Deploy from branch → main branch, root folder.

Then visit the provided URL.
