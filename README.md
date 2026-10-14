# GitHub Slideshow: Developer CI/CD & Automated Technical Presentation Engine

[![Origin: August 2020](https://img.shields.io/badge/Origin-August%202020-blue.svg)](https://github.com/gnarcisi/github-slideshow)
[![Engine: Reveal.js / Jekyll](https://img.shields.io/badge/Engine-Reveal.js%20%7C%20Jekyll-red.svg)](https://revealjs.com/)
[![Focus: Developer Education & CI/CD](https://img.shields.io/badge/Focus-GitOps%20%7C%20CI%2FCD-brightgreen.svg)](https://github.com/gnarcisi)
[![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)](LICENSE)

> **A declarative, Markdown-driven slide presentation and developer education engine powered by Jekyll and Reveal.js.**  
> Originally deployed in August 2020 via the GitHub Learning Lab to master Git branching workflows, pull-request automation, and automated static-site generation.

---

## 1. Technical Context & 2020 Foundation

Completed in August 2020 alongside `big-box-estimate`, **github-slideshow** documents the developer foundational mastery of:
- **GitOps & Branching Strategies:** Multi-branch lifecycle, fast-forward merges, conflict resolution, and pull-request code reviews.
- **Automated Static Site Generation:** Using **Jekyll** (Ruby runtime) and **Reveal.js** to compile pure Markdown slides into responsive, interactive technical presentations deployed via GitHub Pages.
- **Continuous Integration (CI):** Automating deployment checks and branch-protection rules directly from commit hooks.

---

## 2. Core Capabilities

### A. Declarative Slide Authoring
Write technical documentation, system architectures, and engineering walkthroughs in pure Markdown (`_posts/`). Jekyll automatically compiles each markdown document into animated HTML5/CSS3 presentation slides.

### B. Reveal.js Presentation Features
- Responsive touch-enabled slide navigation.
- Code syntax highlighting for multiple programming languages.
- Nested vertical slide transitions for deep-dive technical topics.
- Speaker notes and presentation timing.

---

## 3. Directory Layout

```
github-slideshow/
├── _config.yml         # Jekyll environment configuration & Reveal.js settings
├── _includes/          # Reusable HTML snippets & slide templates
├── _layouts/           # Base presentation layout templates
├── _posts/             # Markdown slide content (compiled on push)
├── index.html          # Dynamic slide deck entry point
├── Gemfile             # Ruby dependency manifest (Jekyll, GitHub Pages gem)
├── LICENSE
└── README.md
```

---

## 4. Local Execution & Preview

To run the presentation engine locally:

```bash
# Clone the repository
git clone https://github.com/gnarcisi/github-slideshow.git
cd github-slideshow

# Install Ruby dependencies
bundle install

# Launch local Jekyll development server
bundle exec jekyll serve
```
Open `http://localhost:4000` in your browser to view the interactive presentation.

---

## 5. Author & Provenance
- **Architect:** Gregory A. Narcisi  
- **Founding Commit:** August 2020  
- **Specialization:** Systems Architect & Technical Evaluator  
- **Contact:** gregnarcisi@gmail.com | [LinkedIn](https://www.linkedin.com/in/greg-narcisi)  
- **License:** MIT Open Source License
