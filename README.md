# Dexter Chua — Personal Website (IS216 WAD2)

A personal portfolio site built for **IS216 Web Application Development II**, tracking my progress through the module — from vanilla HTML/CSS to Bootstrap. This repo also hosts a standalone Fernando Alonso fanpage and a set of Week 2 CSS practice challenges.

🔗 **Live site:** <https://dxterch.github.io/>

> ⚠️ This page is a Work In Progress and will keep evolving as the semester goes on.

## Personal Website (`index.html`)

Built with **Bootstrap 5.3** on top of custom CSS. Sections and components:

- **Responsive navbar** — collapsible on mobile, with a "WAD2 Challenges & Projects" dropdown linking to each challenge and the fanpage
- **Working on-page search** — jumps to the matching section (About, Skills, Projects, Contact, etc.) using simple keyword matching
- **Dismissible alert** — flags the site as a WIP, with an icon and close button
- **About Me + Favorite Travel Destination** — intro card and an autoplaying video card
- **Interactive Singapore map** — hoverable markers (Home / School) with tooltips and a legend
- **Learning Log table** — week-by-week record of topics, deliverables, and assessments, color-coded by row type and scrollable on small screens (`table-responsive`)
- **Skills badges** — pill-style badges for tools used in the module
- **Projects carousel** — cycles through screenshots of the fanpage and Week 2 challenges, each with a caption and a "View Project" link
- **Contact buttons** — outlined buttons linking to Instagram, GitHub, Email, and Telegram
- **Back to Top button** — fixed-position button for quick navigation on long pages

## Project structure

```
index.html          → Personal website (Bootstrap + custom CSS)
styles.css           → Custom styles layered on top of Bootstrap
fanpage.html         → Fernando Alonso fanpage (HTML, CSS, JS all in one file)
Images/              → All photos and graphics used across the site
.nojekyll            → Disables Jekyll processing for GitHub Pages
Lesson 02/
  Challenge1/        → Week 2 - Margin, Padding, Border
  Challenge2/        → Week 2 - Element, Class, ID Selectors
  Challenge3/         → Week 2 - Positioning
```

## Built with

- HTML5
- CSS3 (custom properties, flexbox, grid)
- Bootstrap 5.3 (navbar, dropdown, alert, carousel, badges, buttons, forms)
- Vanilla JavaScript (site search, plus Bootstrap's own JS bundle for interactive components)

---

# Fernando Alonso — Fanpage

An unofficial fanpage for Formula 1 driver Fernando Alonso, built with plain HTML, CSS, and JavaScript (no frameworks or libraries).

🔗 **Live site:** <https://dxterch.github.io/fanpage.html>

## Features

- Animated hero section with a live countdown to the next Grand Prix
- Scrollable career moments timeline
- "On Track / Off Track" tabbed stats and fun facts, with a random fact generator
- Interactive Helmet Hall of Fame and circuit gallery
- A "Lights Out" reaction-time mini game
- Fully responsive layout with a mobile nav menu

## Disclaimer

This is an unofficial fan-made page, not affiliated with Fernando Alonso, Aston Martin, or Formula 1. Built for educational purposes.

---

# Week 2 — CSS Land Challenges

A set of standalone CSS practice exercises themed around a fictional amusement park, "CSS Land." Each challenge ships with a fixed `home.html` (not to be modified) and a `styles.css` skeleton to complete.

🔗 **Live pages:**

- Challenge 1: <https://dxterch.github.io/Lesson%2002/Challenge1/home.html>
- Challenge 2: <https://dxterch.github.io/Lesson%2002/Challenge2/home.html>
- Challenge 3: <https://dxterch.github.io/Lesson%2002/Challenge3/home.html>

| Challenge | Topic | Description |
| --- | --- | --- |
| **Challenge 1** | Margin, Padding, Border | Styles a park welcome page — spacing, borders, fonts, colors, and button hover states. |
| **Challenge 2** | Element, Class, & ID Selectors | Builds an attractions gallery of ride cards using flexbox, hover animations, and image styling. |
| **Challenge 3** | Positioning | Builds an interactive park map with absolutely-positioned markers, hover tooltips, a pinned legend, and a fixed "Back to Top" button. |

Each challenge folder contains:

```
home.html      → fixed markup (do not modify)
styles.css     → CSS skeleton to complete
README.txt     → link to full challenge instructions
```