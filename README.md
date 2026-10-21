<div align="center">
  <h1>ritchegerona.github.io</h1>
  <p><b>Personal portfolio &amp; root site</b> for <a href="https://github.com/ritchegerona">Ritche Gerona</a> — Full-Stack Developer.</p>
  <p>
    <a href="https://ritchegerona.github.io"><img src="https://img.shields.io/badge/live-ritchegerona.github.io-22d3ee.svg" alt="Live site"/></a>
    <img src="https://img.shields.io/badge/framework-none-lightgrey.svg" alt="Framework: none"/>
    <img src="https://img.shields.io/badge/dependencies-0-brightgreen.svg" alt="Dependencies: 0"/>
  </p>
</div>

---

## Overview

This repository hosts my personal portfolio site, served for free via **GitHub Pages** at [ritchegerona.github.io](https://ritchegerona.github.io). It is a single, self-contained static page — no build step, no framework, no dependencies — so it loads fast and is trivial to maintain.

The site introduces me and links out to my open-source projects, tech stack, GitHub activity, and contact channels.

## What's on the page

- **About** — short professional introduction.
- **Tech Stack** — languages, frameworks, and tools I work with.
- **Projects** — cards linking to my public repositories.
- **GitHub Stats** — live activity cards via [github-readme-stats](https://github.com/anuraghazra/github-readme-stats).
- **Let's Connect** — links to GitHub and email.

## Project structure

```
ritchegerona.github.io/
├── index.html      # Entire site (HTML + CSS, single file)
├── profile.png     # Profile photo
└── README.md
```

## Local development

Because it is a plain static site, you can preview it by opening the file directly or serving the folder:

```bash
# Open directly
open index.html

# Or serve locally
python3 -m http.server 8080
# then visit http://localhost:8080
```

To edit the site, change the markup, styles, or content inside `index.html`. The design is a responsive dark theme built with modern CSS (custom properties, flexbox/grid, and media queries) — no CSS framework required.

## Deployment

The site is published automatically by **GitHub Pages** from this repository. After pushing changes to the default branch, GitHub Pages rebuilds and republishes the site within a minute or two.

## License

Content and branding in this repository are personal and © Ritche Gerona. Please don't reuse the design or assets without permission.

Made with ❤️ by Chie
