# Viziogen – AI image, thumbnail & logo generator

A static website (no build step, no API key). It uses the free Pollinations image API.

## Deploy on GitHub Pages
1. Create a new GitHub repo and upload `index.html` and `README.md` (drag and drop the unzipped files).
2. Go to **Settings → Pages**, set Source to **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
3. After a minute your site is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Customize
- Different provider: edit `API_BASE` and `buildUrl()` near the top of the script in `index.html`.
- Add formats, styles or detail chips: edit the `FORMATS`, `STYLES` and `DETAILS` lists.

## Better quality
- Turn on **Enhance my prompt**, use 4 variations, and pick the best.
- For the best results and text rendering, open *Use your own OpenAI key* in the app and paste a key. It is stored only in your browser. Never commit a key to GitHub.
- Use the built-in text editor for titles and logo names instead of asking the AI to draw text.
