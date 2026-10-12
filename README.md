# Selim Fata — Portfolio

A one-file animated portfolio built with plain HTML, CSS and JavaScript. No frameworks and no build step.

**Features:** interactive particle network · animated letter-by-letter hero · text-scramble word rotator · custom cursor · magnetic buttons · 3D tilt project cards with glare · spotlight service cards · live terminal typing · scroll-lit manifesto · animated counters · dual marquee · fully responsive · respects `prefers-reduced-motion`.

## Make it yours

Open `index.html` and edit the `CONFIG` object near the bottom. Every name, link, project, skill and stat on the page comes from it:

- `email`, `socials`: your real email, GitHub and LinkedIn
- `projects`: replace `your-username` in the URLs and add more projects (`hue` sets each card's colour)
- `stats`, `skills`: keep them honest

## Publish on GitHub Pages

1. Create a repo named **`selim7417.github.io`**
2. Upload `index.html` **and the `projects/` folder** (it holds the live 3D dental chart) to it
3. Open **Settings → Pages**, set Source to `main` branch and `/root`
4. Your site goes live at `https://selim7417.github.io`

## Run locally

```bash
python3 -m http.server 5173
```
