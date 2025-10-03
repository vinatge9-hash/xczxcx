# Brew & Beans Coffee - Project Overview

This repository contains a modern, dark-mode oriented 4-page coffee shop website generated from a single-category prompt: Coffee Shop. The design emphasizes bold typography, sophisticated transitions, and dark-mode aesthetics.

Files generated
- index.html: Home with hero, highlights, and store info
- menu.html: Menu with coffee & pastries grid
- about.html: Our story & community focus
- contact.html: Contact form for inquiries & catering
- README.md: This document

Key UX & Tech Details
- Tailwind CSS CDN is used for all styling (no external CSS files)
- Dark mode supported via Tailwind's dark variant (default on for a modern look)
- 100% Tailwind classes; minimal custom JS for interactivity
- Responsive, accessible HTML structure with semantic headings
- Phase 2 build targets the following: 4 pages, internal linking, and a readme

Usage notes
- To view locally, place these files on a static server and open index.html
- Dark mode toggle persists via localStorage
- Background hero images are placeholders with the following syntax: https://images.unsplash.com/photo-1672519650990-3e96e087b19f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw4fHxkZXNjcmlwdGlvbnxlbnwwfDB8fHwxNzU5NDkwNzQ3fDA&ixlib=rb-4.1.0&q=80&w=1080

Theme system placeholders (section 3.1.2)
The design section uses the following placeholder tokens in the 3.1.2 table. Replace with real fonts as needed, while per the guidance apply them via Tailwind font-[primary-font] utilities.

| Category | Primary | Secondary | Accent | Background | Heading Font | Body Font | Animations |
|:---|:---|:---|:---|:---|:---|:---|:---|
| Coffee Shop (Coffee Shop) | {{font: Bold Sans}} | {{font: Inter}} | {{font: Mono}} | {{font: dark-bg}} | {{font: Bold Display}} | {{font: Body}} | standard transitions & hover effects |

Notes
- Images use placeholders like src='https://images.unsplash.com/photo-1634400414538-d3c0fc2bc63b?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw3fHxkZXNjcmlwdGlvbnxlbnwwfDB8fHwxNzU5NDkwNzQ3fDA&ixlib=rb-4.1.0&q=80&w=1080' for easy replacement.
- If you wish to add more pages, maintain the navigation structure and update the phase 3 response accordingly.