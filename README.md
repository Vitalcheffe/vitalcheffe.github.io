<div align="center">

# vitalcheffe.github.io

### Personal portfolio — systems engineering, applied physics, and quantitative finance research by Amine Harch El Korane.

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-static%20portfolio-E34F26.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Status: Live](https://img.shields.io/badge/status-live%20%E2%80%A2%20vitalcheffe.github.io-brightgreen.svg)](https://vitalcheffe.github.io)
[![GitHub Pages](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-181717.svg)](https://pages.github.com)

Single-page static site · 6 flagship projects · 8 skill domains · MathJax-rendered engineering deep dives

</div>

---

## Overview

This repository hosts my personal portfolio at [vitalcheffe.github.io](https://vitalcheffe.github.io). It is a single-page static HTML site — no framework, no build step, no JavaScript bundle — built to showcase six flagship engineering projects, eight skill domains, and three engineering deep dives with MathJax-rendered mathematical content.

This is a **portfolio**, not a product. It exists to give a reviewer (admissions officer, recruiter, collaborator) a 90-second overview of what I build, why I build it, and the math behind it. Every project linked has a real GitHub repository with code, documentation, and commit history.

---

## Why I built this

I built this portfolio at 15, in Casablanca, after realizing that my GitHub profile had 89 repositories but no front door. A reviewer landing on `github.com/Vitalcheffe` saw a wall of repos with no narrative — no sense of which projects mattered, what they proved, or what I had learned from them. The portfolio exists to impose order on that chaos.

The design choice — single static HTML file, no framework, no build step — is deliberate. A portfolio should load in under a second on a 3G connection. It should work with JavaScript disabled. It should be readable by a crawler, a screen reader, and an admissions officer on a phone in an airport. Next.js, React, and the modern frontend stack are tools I use daily for real products; this portfolio is not a product, it is a document.

---

## Table of contents

- [Overview](#overview)
- [Why I built this](#why-i-built-this)
- [Featured projects](#featured-projects)
- [Engineering deep dives](#engineering-deep-dives)
- [Skills](#skills)
- [Design choices](#design-choices)
- [Run it](#run-it)
- [Stack](#stack)
- [Documentation](#documentation)
- [Limitations](#limitations)
- [License](#license)

---

## Featured projects

The portfolio showcases six flagship projects, each with a real GitHub repository behind it:

| Project | What it is | Repository |
|---------|-----------|------------|
| **AEGIS / Tessera Mk.II** | Autonomous multi-agent coordination framework — UKF estimation, BFT sensor fusion, real-time trajectory prediction | [Vitalcheffe/Aegis](https://github.com/Vitalcheffe/Aegis) |
| **NEXUS Platform** | Real-time geospatial intelligence engine — 35+ live sources, 6D correlation, 92 Telegram channels | [Vitalcheffe/Nexus-Osint](https://github.com/Vitalcheffe/Nexus-Osint) |
| **Sense-Act Engine** | Oil market sentiment analysis — FinBERT NLP pipeline, genetic algorithm signal selection, shadow trading backtest | [Vitalcheffe/sense-act-core](https://github.com/Vitalcheffe/sense-act-core) |
| **WRAP Nebula** | Local-first agentic AI kernel — zero-trust architecture, 100% private, runs on-device | [Vitalcheffe/Wrap](https://github.com/Vitalcheffe/Wrap) |
| **xanLens** | Open-source GEO audit engine — ask 7 AI engines if they know a brand | [Vitalcheffe/xanlens](https://github.com/Vitalcheffe/xanlens) |
| **OpFlow** | Lightweight operations platform for small local businesses | [Vitalcheffe/opflow](https://github.com/Vitalcheffe/opflow) |

Each project card on the portfolio links directly to its GitHub repository.

---

## Engineering deep dives

Three deep dives are documented with MathJax-rendered mathematical content, accessible directly on the portfolio:

### AEGIS — Autonomous Interceptor Engine

The math behind multi-agent aerial coordination: Unscented Kalman Filter derivation, BFT consensus protocols, spectral sensor fusion. Covers sigma-point generation, covariance propagation, and the measurement update equations.

### NEXUS — Real-Time OSINT Engine

The architecture behind real-time geospatial intelligence: source ingestion, 6D correlation (lat, lon, alt, time, source, confidence), and the confidence-weighted aggregation across 35+ live data streams.

### Sense-Act — Sentiment Arbitrage Engine

The quantitative pipeline: FinBERT fine-tuning, shadow trading simulation, genetic algorithm signal selection. Includes the Sharpe ratio calculation, maximum drawdown formula, and the fitness function used for signal evolution.

---

## Skills

Eight skill domains, each with specific competencies:

| Domain | Competencies |
|--------|-------------|
| **C / C++ Systems** | Embedded systems, real-time constraints, memory safety |
| **Python Scientific** | Automation, data pipelines, ML research |
| **Rust Performance** | Systems programming, zero-cost abstractions |
| **Electronics** | PCB design, embedded hardware, RF |
| **Ballistics** | External ballistics, terminal ballistics |
| **Mathematics** | Linear algebra, ODEs, statistics, control theory |
| **TypeScript Full-Stack** | Next.js, React, Node.js, real-time web |
| **Physics** | Mechanics, electromagnetism, thermodynamics |

---

## Design choices

**Single static HTML file.** No framework, no build step, no JavaScript bundle. The site is one `index.html` file with inline CSS and minimal inline JavaScript. This is deliberate — a portfolio should be a document, not an application.

**Custom typography.** Syne for display, DM Sans for body, DM Mono for code. No Inter, no system fonts. Typography is part of the identity.

**MathJax for math.** Engineering deep dives render LaTeX equations via MathJax. No images of equations, no screenshots — real, selectable, accessible math.

**Grid texture background.** A subtle grid pattern (`body::before` with `position: fixed`) signals engineering without being noisy.

**No dark mode toggle.** The portfolio is light-mode only. Dark mode is a feature for tools people use daily; a portfolio is read once. Light mode is the default reading mode for serious documents.

---

## Run it

```bash
# Clone
git clone https://github.com/Vitalcheffe/vitalcheffe.github.io.git
cd vitalcheffe.github.io

# No build step. Just open index.html in a browser.
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

Or visit the live site: [vitalcheffe.github.io](https://vitalcheffe.github.io)

---

## Stack

| Layer | Technology |
|-------|-----------|
| Markup | Single static HTML5 file (49KB) |
| Styling | Inline CSS, custom design tokens, no framework |
| Math | MathJax 3 (LaTeX rendering) |
| Typography | Syne (display), DM Sans (body), DM Mono (code) — Google Fonts |
| Hosting | GitHub Pages |
| Build step | None |

---

## Documentation

| Resource | Purpose |
|----------|---------|
| [index.html](./index.html) | The portfolio itself — single static file |
| [LICENSE](./LICENSE) | MIT license |
| Live site | [vitalcheffe.github.io](https://vitalcheffe.github.io) |

---

## Limitations

Stated explicitly, because even a portfolio should be honest about what it is not:

1. **Single-page, no routing.** The portfolio is one HTML file with anchor-based navigation. There is no client-side routing, no separate pages. This is a deliberate trade-off for simplicity and load speed, but it means the portfolio does not scale to dozens of projects without becoming a very long scroll.

2. **No content management.** Project listings, skills, and deep dives are hardcoded in `index.html`. Adding a project requires editing the HTML directly. A CMS would be overkill for a portfolio of this size; a static site generator (Astro, Eleventy) would be the right next step if the project count grows beyond 10.

3. **No analytics.** The portfolio does not track visitors. This is deliberate — I do not want to optimize the portfolio for engagement metrics. If a reviewer reads it, good. If they don't, I will not know.

4. **Light mode only.** No dark mode toggle. See [Design choices](#design-choices) for the reasoning. If a reviewer strongly prefers dark mode, they can use their browser's forced dark mode.

5. **MathJax dependency on a CDN.** Math rendering requires a network request to `cdn.jsdelivr.net`. If the CDN is down, equations do not render. An offline fallback (vendoring MathJax locally) would add ~5MB to the repo and is not currently implemented.

---

## License

MIT — see [LICENSE](./LICENSE). The license applies to the portfolio source code (HTML, CSS, JavaScript inline). Project names, descriptions, and the engineering deep dives are my original writing — please do not copy them without attribution.

---

<div align="center">
<sub>Built by Amine Harch El Korane · Casablanca, Morocco · 2026</sub><br>
<sub>"The portfolio is not the work. The work is in the repositories. The portfolio is the door."</sub>
</div>
