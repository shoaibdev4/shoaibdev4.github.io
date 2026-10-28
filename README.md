# Shoaib Ahmad — 3D Tailwind portfolio

A responsive, accessible, multipage CV website with compiled Tailwind CSS, CSS 3D artwork, project filtering, individual project pages, and reduced-motion support. Content is grounded in Shoaib Ahmad’s professional and original CVs. No employer dates or performance claims have been invented. The scene and project thumbnails are original abstract CSS artwork, not client screenshots.

## Run

```sh
npm ci
npm run build
npm run preview
```

Open http://localhost:4173. The compiled static website is in `dist/` and can also be opened from `dist/index.html`.

## GitHub publication

Connected GitHub account: shoaibdev4. Intended public repository: `shoaibdev4.github.io`. Before creating it, verify the signed-in account and whether this repository already exists; do not overwrite an existing website.

Push this directory to the public repository on `main`. In Settings → Pages, select GitHub Actions. The included workflow builds and deploys `dist/`. Intended URL (not yet deployed): https://shoaibdev4.github.io/

If using a different repository or domain, update canonical and Open Graph URLs in every HTML page, plus sitemap.xml and robots.txt before publication.

## Search visibility

Includes page-specific titles and descriptions, semantic HTML, canonical URLs, Person structured data, sitemap and robots.txt. After deployment verify ownership in Google Search Console and submit sitemap.xml. Google controls crawling, indexing and ranking; first place cannot be guaranteed.

## Content

6 main pages, 11 project detail pages, and a 404 page. Source styling: src/input.css. Content: dist/*.html. Interactions: dist/assets/app.js. Contact details are taken from the CV; date of birth is omitted.

## Publication

Public source: https://github.com/shoaibdev4/shoaibdev4.github.io
Website: https://shoaibdev4.github.io/
