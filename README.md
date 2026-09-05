# Dexter Chua — Personal Website (IS216 WAD2)

A personal portfolio site built for **IS216 Web Application Development II**, tracking my progress through the module — from vanilla HTML/CSS to Bootstrap. This repo also hosts a standalone Fernando Alonso fanpage and a set of weekly practice challenges.

🔗 **Live site:** <https://dxterch.github.io/>
> ⚠️ This page is a Work In Progress and will keep evolving as the semester goes on.

## Personal Website (`index.html`)

Built with **Bootstrap 5.3** on top of custom CSS. Sections and components:

- **Responsive navbar** — collapsible on mobile, with a "Challenges & Projects" dropdown linking to each weekly challenge and the fanpage
- **Dismissible alert** — flags the site as a WIP, with an icon and close button
- **About Me + Favorite Travel Destination** — intro card and an autoplaying video card
- **Interactive Singapore map** — hoverable markers (Home / School) with tooltips and a legend; on mobile, the legend is hidden behind a toggle button to save space
- **Learning Log** — week-by-week record of topics, deliverables, and assessments, split into three tabs (Weeks 1–6 / Weeks 7–13 / Final Exam), color-coded by row type, and horizontally scrollable on small screens
- **Projects carousel** — cycles through screenshots of the fanpage and weekly challenges; quick-jump pills above the carousel let you skip straight to a project; clicking any image opens it full-size in a modal with a caption
- **"Get to Know Me" card** — Skills & Tools grouped by category (Core / Learning Now / Tooling) alongside a Contact list of Instagram, GitHub, Email, and Telegram
- **Back to Top button** — fixed-position button for quick navigation on long pages

> Note: the navbar's search bar is currently UI-only and not yet wired up to actually filter or jump to sections.

## Project structure

```
index.html          → Personal website (Bootstrap + custom CSS)
styles.css           → Custom styles layered on top of Bootstrap
fanpage.html         → Fernando Alonso fanpage (HTML, CSS, JS all in one file)
Images/              → All photos and graphics used across the site
Video/               → Video assets used on the personal website
.nojekyll            → Disables Jekyll processing for GitHub Pages
Lesson 02/Challenge1/ → Week 2 - Margin, Padding, Border
Lesson 02/Challenge2/ → Week 2 - Element, Class, ID Selectors
Lesson 02/Challenge3/ → Week 2 - Positioning
Lesson 03/Challenge1/ → Week 3 - Bootstrap Grid & Typography
```

## Built with

- HTML5
- CSS3 (custom properties, flexbox, grid)
- Bootstrap 5.3 (navbar, dropdown, alert, carousel, modal, nav-pills, tabs, list-group, badges, buttons, grid system)
- Vanilla JavaScript (legend toggle, modal image swap, carousel/pill sync, plus Bootstrap's own JS bundle for interactive components)

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

# Lesson 02 — CSS Land Challenges

A set of standalone CSS practice exercises themed around a fictional amusement park, "CSS Land." Each challenge ships with a fixed `home.html` (not to be modified) and a `styles.css` skeleton to complete.

🔗 **Live pages:**

- Challenge 1: <https://dxterch.github.io/Lesson%2002/Challenge1/home.html>
- Challenge 2: <https://dxterch.github.io/Lesson%2002/Challenge2/home.html>
- Challenge 3: <https://dxterch.github.io/Lesson%2002/Challenge3/home.html>

| Challenge       | Topic                          | Description                                                                                                                           |
| --------------- | ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------- |
| **Challenge 1** | Margin, Padding, Border        | Styles a park welcome page — spacing, borders, fonts, colors, and button hover states.                                                |
| **Challenge 2** | Element, Class, & ID Selectors | Builds an attractions gallery of ride cards using flexbox, hover animations, and image styling.                                       |
| **Challenge 3** | Positioning                    | Builds an interactive park map with absolutely-positioned markers, hover tooltips, a pinned legend, and a fixed "Back to Top" button. |

Each challenge folder contains:

```
home.html      → fixed markup (do not modify)
styles.css     → CSS skeleton to complete
README.txt     → link to full challenge instructions
```

---

# Lesson 03 — Bootstrap Challenges

Practice exercises introducing **Bootstrap 5**, converting bare HTML markup into responsive, styled pages using Bootstrap's grid system and utility classes instead of hand-rolled CSS.

🔗 **Live page:**

- Challenge 1: <https://dxterch.github.io/Lesson%2003/Challenge1/justin.html>

| Challenge       | Topic                        | Description                                                                                                                    |
| --------------- | ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Challenge 1** | Bootstrap Grid & Typography   | Rebuilds a simple "Justin Bieber Fan Page" — centers the heading/intro text and lays out a photo + bio section responsively using Bootstrap's `container`, `row`, and `col` grid classes. |

Each challenge folder contains:

```
justin.html          → HTML markup using Bootstrap 5.3 (via CDN)
justin_concert.jpg    → Image used in the page
styles.css            → Supplementary custom styles on top of Bootstrap
```