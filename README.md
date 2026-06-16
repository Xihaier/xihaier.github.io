# Personal Website

Source code for my personal academic website hosted with GitHub Pages.

Live site: <https://xihaier.github.io>

## Tech Stack

- Static HTML, CSS, and JavaScript
- GitHub Pages / Jekyll
- Bootstrap for the main homepage layout
- Bulma for project pages
- jQuery, MathJax, Font Awesome, and Academicons

## Project Structure

```text
.
├── index.html              # Main personal website
├── _config.yml             # GitHub Pages / Jekyll config
├── assets/
│   ├── css/                # Shared styles and vendor CSS
│   ├── js/                 # Shared scripts and vendor JS
│   └── img/                # Homepage and publication images
└── projects/               # Individual project pages
    ├── CVPR-2026-DINR/
    ├── ICLR-2024-MMGN/
    └── ICML-2024-HiNOTE/
```

## Local Development

This site has no package manager dependencies or build step.

Install dependencies:

```bash
# Nothing to install
```

Run a local development server:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Updating Content

- Edit `index.html` for homepage content and publications.
- Add homepage images under `assets/img/`.
- Add or update project pages under `projects/`.

