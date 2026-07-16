# Roberto Pires Almeida: Portfolio

Personal portfolio website. Live demos:

- Platform game: https://synckser.github.io/game-final/
- Data visualisations: https://synckser.github.io/data-vis/

## How to publish this on GitHub Pages

To get the best possible address, **https://synckser.github.io** (no path after it), the repository must be named exactly `synckser.github.io`:

1. Go to github.com → **New repository**
2. Name it `synckser.github.io` (must match your username exactly), set it to **Public**, create it
3. Click **Add file → Upload files**, upload `index.html` (and this README), commit
4. Wait a minute or two, then visit **https://synckser.github.io**. Done

If you'd rather keep it as a normal project repo (like your other two), name it anything (e.g. `portfolio`), upload the files, then go to **Settings → Pages → Source: Deploy from a branch → main → / (root) → Save**. It will publish at `https://synckser.github.io/portfolio/`.

## Updating it later

Edit `index.html` directly on GitHub (pencil icon) or push changes with git. Pages redeploys automatically within a minute.

## When Draw & Learn goes live

Open `index.html`, find the Draw & Learn card, and replace the line
`<span class="status">Going through App Store submission</span>`
with a link to the App Store page, e.g.
`<a class="go" href="YOUR_APP_STORE_LINK">View on the App Store &rarr;</a>`
