# KIIT Moodle — Rebuilt UI

A clean, modern redesign of the [KIIT Moodle LMS](https://kiitmoodle.in/my/) dashboard — built with pure HTML and CSS, no frameworks, no dependencies.
KIIT University's Moodle LMS gets the job done, but the interface is dated and cluttered. This project is a full front-end rebuild of the student-facing dashboard — same structure, same data, cleaner look and feel.

It's a static HTML/CSS replica, not connected to any backend. Think of it as a UI prototype or a personal portfolio piece showing what the LMS *could* look like.

---

## Pages

| File | Description |
|---|---|
| `index.html` | Main dashboard — enrolled courses, stats, mini calendar |
| `courses.html` | Course detail view with expandable topic sections and resources |
| `grades.html` | Grades overview |
| `calendar.html` | Academic calendar |
| `profile.html` | Student profile and private files |
| `shared.css` | Shared design tokens and component styles |

---

## Features

- **Warm Notion-inspired design** — off-white background, clean typography, subtle borders
- **Sticky sidebar navigation** with active state highlighting
- **Course cards** with colour-coded stripes per subject
- **Expandable topic sections** on the courses page — click to reveal resources
- **Mini calendar** rendered in pure JavaScript, no libraries
- **In-browser document viewer** — intercepts PDF/DOCX/PPTX link clicks and opens them in a modal with Google Docs fallback for non-PDF formats
- **Responsive layout** — sidebar collapses on mobile
- **Fade-up animations** with staggered timing on page load
- **Stat cards** showing enrolled courses, upcoming events, and notifications at a glance

---

## Tech Stack

| | |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | [DM Sans](https://fonts.google.com/specimen/DM+Sans) + [DM Mono](https://fonts.google.com/specimen/DM+Mono) via Google Fonts |
| Hosting | GitHub Pages |

No build tools. No npm. No frameworks. Open any `.html` file directly in a browser and it works.

---

## Screenshots

> Dashboard

![Dashboard](https://asif-ahaan.github.io/kiit-moodle-rebuilt/index.html)

---

## Project Structure

```
kiit-moodle-rebuilt/
├── index.html       # Dashboard
├── courses.html     # My Courses
├── grades.html      # Grades
├── calendar.html    # Calendar
├── profile.html     # Profile & Files
└── shared.css       # Global styles
```

---

## Getting Started

No setup required. Just clone and open.

```bash
git clone https://github.com/Asif-Ahaan/kiit-moodle-rebuilt.git
cd kiit-moodle-rebuilt
# Open index.html in your browser
```

Or visit the live demo directly:  
👉 https://asif-ahaan.github.io/kiit-moodle-rebuilt/index.html

---

## Motivation

The original KIIT Moodle UI works but feels heavy — multiple nested iframes, inconsistent spacing, and an outdated colour palette. This rebuild started as a personal experiment to see how much of the student experience could be improved with just plain HTML and CSS, without touching any backend or Moodle configuration.

---

## Disclaimer

This is an **unofficial, independent UI project** and is not affiliated with, endorsed by, or connected to KIIT University or Moodle in any way. All course names and student data shown are fictional placeholders for demonstration purposes.

---

## Author

**Sheikh Asif** — 23051951, KIIT University  
GitHub: [@Asif-Ahaan](https://github.com/Asif-Ahaan)
