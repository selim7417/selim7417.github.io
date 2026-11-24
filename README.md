# Selim El Fata — Portfolio

**Live:** https://selim7417.github.io

One animated page with no frameworks and no build step. It has five projects with full case studies, filters, a quick menu (⌘K / Ctrl K), a live Beirut clock and a downloadable CV.

## Edit it

Everything on the page comes from the `CONFIG` object near the bottom of `index.html`: your details, projects, case studies, experience, services and skills.

- **Add a project:** copy one entry in `projects`, change the text, and put its images in `projects/<name>/`.
- **Share one project:** every case study has its own link, like `https://selim7417.github.io/#/work/safelight`.
- **Link preview:** `og.jpg` is the image shown when the link is shared on WhatsApp, LinkedIn and so on.
- **CV:** `cv/cv.html` is the source; `cv/Selim-El-Fata-CV.pdf` is the file people download.

## Run locally

```bash
python3 -m http.server 5180
```
