# Viziogen – AI image, thumbnail & logo generator

A static website (no build step, no API key). Free provider: AI Horde (no key). Best quality: your own OpenAI key.

## Deploy on GitHub Pages
1. Create a new GitHub repo and upload `index.html` and `README.md` (drag and drop the unzipped files).
2. Go to **Settings → Pages**, set Source to **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
3. After a minute your site is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Customize
- Different provider: edit `API_BASE` and `buildUrl()` near the top of the script in `index.html`.
- Add formats, styles or detail chips: edit the `FORMATS`, `STYLES` and `DETAILS` lists.

## Providers
- **Free (AI Horde):** no account or key. Community GPUs, so it can queue for a minute or more, and anonymous images are small (about 512px) and basic quality.
- **OpenAI (your key):** best quality and text. Paste your key in the app; it is stored only in your browser. Never commit a key to GitHub.

Tip: use the built-in text editor for titles and logo names instead of asking the AI to draw text.
