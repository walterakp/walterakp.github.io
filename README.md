# walterakp.github.io

Landing page for my GitHub Pages projects, served at
**https://github.mowdesigns.ng**

Each project lives in its own repo and is published as a GitHub Pages
project site, so it appears under this domain automatically:

| Project | URL |
| --- | --- |
| Jumping Game (Roomba Cat) | https://github.mowdesigns.ng/jumping-game/ |
| Rock Paper Scissors UI | https://github.mowdesigns.ng/rock-paper-scissors-ui/ |
| Calculator | https://github.mowdesigns.ng/calculator/ |
| Escape the Evil AI | https://github.mowdesigns.ng/escape-the-evil-ai/ |

## Adding another project

1. In the project repo: **Settings → Pages → Source: `main` / root**.
2. Add a card for it in `index.html` here, linking to `repo-name/`.

Do **not** set a custom domain on the project repos — the domain belongs to
this repo only, and project sites inherit it.

Use relative asset paths (`style.css`, not `/style.css`) in project repos, or
they will break when served from a subfolder.
