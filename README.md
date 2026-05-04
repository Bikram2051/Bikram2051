# bikram2051.github.io

My personal portfolio site - live at **[bikram2051.github.io](https://bikram2051.github.io)**.

A single-page portfolio for my work as a data analyst and Master of Data Science student at Swinburne University. Built from scratch with plain HTML, CSS, and a small amount of vanilla JavaScript - no frameworks, no build step, no npm. Just a single `index.html` file deployed straight to GitHub Pages.

---

## About

I'm Bikram Bhattarai - a data analyst based in Melbourne with nearly four years of offshore experience across market and product insights, reporting, and product analytics. Currently completing a Master of Data Science at Swinburne, with a marketing MBA on the commercial side and working knowledge of SQL, Python, R, Tableau, and Power BI on the technical side.

This site is the long-form version of my CV - the projects, the journey from product ops to analytics to data science, and how to get in touch.

---

## What's on the site

- **About** - who I am and how I got into data.
- **Skills & tools** - the working stack: Python, R, SQL, Tableau, Power BI, plus the analytics methods and tools I use day-to-day.
- **Projects** - selected work across NLP (Transformers / BERT), financial risk modelling, EV adoption, lending portfolios, HR, and sales dashboards.
- **Experience & education** - the timeline, including the Master of Data Science, MBA, and prior roles at KeyGap (Bangalore) and PowerWeave (Mumbai).
- **Contact** - email, phone, LinkedIn, GitHub, Tableau Public.

---

## Tech stack

| Layer | What I used |
|---|---|
| Markup | HTML5 |
| Styling | CSS custom properties (design tokens), CSS Grid, Flexbox |
| Typography | Fraunces (display), Inter Tight (UI), JetBrains Mono (code) - via Google Fonts |
| Interactivity | Vanilla JavaScript - typing effect, scroll-reveal via IntersectionObserver, mobile nav toggle |
| Hosting | GitHub Pages |
| Build step | None |

The whole thing is one `index.html` file with inline CSS and JS - deliberately. It keeps the codebase honest, the page fast, and the deploy story simple.

---

## Running it locally

Clone and open - that's it.

```bash
git clone https://github.com/Bikram2051/bikram2051.github.io.git
cd bikram2051.github.io
open index.html        # macOS
# or: xdg-open index.html   (Linux)
# or: start index.html      (Windows)
```

If you'd rather run a local server (e.g. for cleaner relative paths or to test on your phone over LAN):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

---

## Project structure

```
.
├── index.html                     # The whole site - markup, styling, scripts
├── assets/
│   ├── bikram.jpg                 # Profile photo
│   ├── hero.png                   # Hero badge image
│   └── projects/                  # Project cover screenshots (16:9 recommended)
│       ├── sentiment-analysis.png
│       ├── ev-population.png
│       ├── hr-analytics.png
│       ├── bank-loan.png
│       ├── bankruptcy-prediction.png
│       └── sales-dashboard.png
└── README.md                      # You are here
```

---

## Deployment

GitHub Pages serves the `main` branch from the repo root. Any push to `main` redeploys the site within a minute or two.

Repo settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)`.

---

## Accessibility & performance notes

A few small things I cared about while building this:

- **Reduced motion support** - the typing effect and scroll-reveal animations both respect `prefers-reduced-motion`. If you have it set, animations are skipped and content shows instantly.
- **Progressive enhancement** - the scroll-reveal CSS only hides elements once JavaScript adds a `js-reveal` class on load. If JS is disabled, the page still renders fully.
- **Semantic HTML** - proper landmarks (`<header>`, `<main>`, `<section>`, `<footer>`), descriptive alt text, ARIA labels on the mobile nav toggle.
- **Sticky nav with scroll feedback** - a subtle border appears on the nav once you scroll past the top, so it doesn't sit there as a floating bar with no relationship to the page.

---

## Contact

- **Email:** vikrambhattarai1994@gmail.com
- **LinkedIn:** [linkedin.com/in/bikram2051](https://www.linkedin.com/in/bikram2051/)
- **Tableau Public:** [public.tableau.com/app/profile/bikram.bhattarai](https://public.tableau.com/app/profile/bikram.bhattarai/vizzes)

---

*Built from scratch with HTML/CSS/JS. Hosted on GitHub Pages.*
