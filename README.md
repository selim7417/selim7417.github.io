# Selim Fata — Portfolio

A one-file animated portfolio built with plain HTML, CSS and JavaScript. No frameworks and no build step.

**Features:** interactive particle network · animated letter-by-letter hero · text-scramble word rotator · custom cursor · magnetic buttons · 3D tilt project cards with glare · spotlight service cards · live terminal typing · scroll-lit manifesto · animated counters · dual marquee · fully responsive · respects `prefers-reduced-motion`.

## Make it yours

Open `index.html` and edit the `CONFIG` object near the bottom. Every name, link, project and skill on the page comes from it:

- `email`, `socials`: your real email, GitHub and LinkedIn
- `projects`: add or edit project cards (`hue` sets each card's colour, `image` adds a screenshot)
- `skills`: the tools you use

## Publish on GitHub Pages

1. Create a repo named **`selim7417.github.io`**
2. Upload `index.html` **and the `projects/` folder** (screenshots, the 3D dental chart and the Pro-denticare site) to it
3. Open **Settings → Pages**, set Source to `main` branch and `/root`
4. Your site goes live at `https://selim7417.github.io`

## Run locally

```bash
python3 -m http.server 5173
```
