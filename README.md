# PlaNxt – landing page

PlaNxt is an AI travel agent for groups: plan on the web, travel on WhatsApp.
*Plan it · Live it · Relive it.*

This is a static website: a single `index.html` with no build step.

## Run it locally

Option 1: double-click `index.html` to open it in your browser.

Option 2 (closer to a real server), from this folder in Terminal:

    python3 -m http.server 8000

then open http://localhost:8000

## Deploy

Any static host works with zero configuration:
- **GitHub Pages:** push to GitHub, then Settings → Pages → deploy from the `main` branch, root folder.
- **Netlify / Vercel:** import the repo; leave the build command empty and the output directory as the root.
