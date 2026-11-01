# Ikejimba Age Grade Foundation â€” "Aku Ruo Ulo"

Live site: **https://ikejimba.onrender.com/**

## What this is
A single-page site for the Ikejimba Age Grade Foundation of Akoliufu Alayi, Bende LGA, Abia State. One age grade, organised as a development foundation, publishing a repeatable model for closing the grassroots digital divide â€” beginning with the **Aku Ruo Ulo Digital Bridge**.

## Structure
- `public/index.html` â€” the complete site (HTML, CSS and JavaScript in one file)
- `public/assets/` â€” photography, crest, favicon, touch icon and the 1200Ã—630 social card
- `public/robots.txt`, `public/sitemap.xml`, `public/site.webmanifest` â€” crawl and install metadata
- `index.html` â€” mirror at the repo root, kept byte-identical to `public/index.html`
- `docs/` â€” review, prompts, content guide, evolution plan, image attributions and the untouched original file

## Editing content
Open `public/index.html`. Page copy lives in the markup; events, journal posts, gallery captions and page titles live in the JavaScript arrays near the bottom (`EV`, `POSTS`, `CATS`, `T`, `SRC`, `META`). See `docs/CONTENT-GUIDE.md`.

After editing, copy `public/index.html` over `index.html` so both stay in sync, then commit and push.

## Deployment
Render static site **`ikejimba`** (workspace KORA), connected to
`erpforgeafrica-dotcom/ikejimba-aku-ruo-ulo-site`, branch `main`.

- Build command: none
- Publish directory: `public`
- Auto-deploy: on every push to `main`

## External dependencies
- three.js (r128) from cdnjs â€” slide 2; falls back to the CSS doorway if unavailable
- Leaflet + OpenStreetMap tiles â€” the Ground page map
- Google Fonts â€” Cinzel, Cormorant Garamond, Noto Serif (Igbo diacritics)

## Placeholders to replace before a custom-domain launch
- Contact addresses: `hello@ikejimba.org`, `partnerships@ikejimba.org`
- Canonical, Open Graph and JSON-LD URLs currently point at `ikejimba.onrender.com`; switch them to the custom domain once it is live
- Office-holder names are published after each Annual Assembly

