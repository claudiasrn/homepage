# Personal Portfolio Homepage

A responsive personal portfolio homepage built as the final project for The Odin Project's Advanced HTML & CSS course. The layout matches provided desktop, tablet, and mobile designs and adapts smoothly across viewports from 320px to 1920px wide.

## Overview

The page has three sections:

- **Header / About me** — intro photo and short bio, with links to GitHub and LinkedIn
- **My work** — a grid of project cards, each with a screenshot, title, live-site and GitHub links, and a one-line description
- **Contact** — email, location, and social links, with a closing portrait

## Built with

- Semantic HTML5
- CSS3 — Flexbox, CSS Grid, `shape-outside` for text wrap around the header photo, custom properties for theming
- Responsive design via media queries (mobile-first breakpoints at 660px and 880px)
- Google Fonts: Playfair Display, Karla
- Icons from [Devicon](https://devicon.dev/) and [Material Design Icons](https://materialdesignicons.com/)

## What I practiced

- Translating a multi-viewport design brief into a single responsive layout rather than separate breakpoint-specific rebuilds
- Using `shape-outside` to wrap body text around an irregularly shaped image
- CSS Grid for the project card layout, switching column count by breakpoint
- Organizing reusable custom properties (`:root` variables) for a consistent color palette
- Accessible link states (`:focus-visible`, `aria-disabled` for an in-progress project's inactive link)