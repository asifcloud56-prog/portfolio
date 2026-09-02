# Asif Ali — DevOps Engineer Portfolio

A responsive, single-page portfolio website showcasing my skills, projects, and experience
as a DevOps/Platform Engineer specializing in cloud infrastructure, CI/CD automation, and
container orchestration.

**Live Site:** [asifcloud56-prog.github.io/portfolio](https://asifcloud56-prog.github.io/portfolio/)

## Overview

This portfolio is built as a clean, single-file HTML site with smooth scroll navigation,
animated sections, and a fully responsive layout that works across desktop and mobile.

## Sections

| Section     | Description                                                          |
|-------------|------------------------------------------------------------------------|
| **Home**    | Introduction with a typing animation cycling through core skills       |
| **About**   | Background, contact details, and downloadable CV                       |
| **Skills**  | Categorized DevOps skill set — Linux, Cloud/IaC, Containers, CI/CD, Scripting, Monitoring |
| **Portfolio** | Real, working DevOps projects with links to source code              |
| **Contact** | Contact form and direct contact information                           |

## Featured Project

One of the portfolio projects links to a fully functional, tested CI/CD pipeline:
**[docker-cicd-demo](https://github.com/asifcloud56-prog/docker-cicd-demo)** — a Dockerized
Flask app with an automated GitHub Actions pipeline (lint → test → build → push to Docker Hub).

## Tech Stack

- **HTML5 / CSS3** — structure and custom styling
- **Bootstrap 5** — responsive grid and components
- **AOS (Animate On Scroll)** — scroll-triggered animations
- **Font Awesome** — icons
- **Vanilla JavaScript** — typing animation, smooth scroll, navbar behavior

## Run Locally

No build step required — it's a static site.

```bash
git clone https://github.com/asifcloud56-prog/portfolio.git
cd portfolio
```

Then open `index.html` directly in a browser, or serve it locally:

```bash
python -m http.server 8000
```

Visit `http://localhost:8000`.

## Deployment

This site is deployed via **GitHub Pages**, directly from the `main` branch. Any change
pushed to `main` goes live within a minute or two — no separate build/deploy step needed.

## File Structure

```
portfolio/
├── index.html              # Main site (all HTML/CSS/JS in one file)
├── profile.jpeg             # Profile photo
└── Asif_Ali_DevOps.pdf       # Downloadable CV
```

## Contact

- **Email:** asifcloud56@gmail.com
- **Phone:** +92 335 3731483
- **LinkedIn:** [linkedin.com/in/asif-ali-shar-0a22323b8](https://linkedin.com/in/asif-ali-shar-0a22323b8)
- **GitHub:** [github.com/asifcloud56-prog](https://github.com/asifcloud56-prog)
- **Location:** Karachi, Pakistan
