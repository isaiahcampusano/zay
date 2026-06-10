# Portfolio

## Goal
Building product systems across fintech, frontend development, and consumer UX.

---

## Checkpoint 1 — Complete

### What was built
- Full HTML structure with semantic sections
- Navigation with working anchor links
- Hero with badges, name, role, CTA buttons, and meta row
- Experience section with styled cards
- Project cards with accent bars, category labels, tags, and read-more links
- Blog section with three article cards
- Contact section with email, LinkedIn, and GitHub links
- Footer

### What was improved
- Eliminated dead space — all sections use consistent `padding: 6rem 0` inside a `max-width: 1100px` container
- Replaced conflicting CSS blocks with a single clean token system
- Introduced Richard Phan-style card grid: `gap: 1px` wrapper border with shared hairline dividers
- Added colored 3px accent bar per card for visual identity
- Light/dark mode via CSS custom properties on `[data-theme]` with localStorage persistence
- Scroll-triggered fade-up animations via `IntersectionObserver`
- Sticky nav with frosted-glass blur on scroll
- `prefers-reduced-motion` respected

---

## Current status
- Site is live
- Checkpoint 1 complete — full layout, card system, and interactions built
- Real content (email, links, resume PDF) still needs to be swapped in
- Hero image removed pending a photo asset
- About section not yet added

---

## Desired structure
1. Hero
2. About / Positioning
3. Experience
4. Projects
5. Blog
6. Contact

## Navigation labels
- About
- Experience
- Projects
- Blog
- Contact

## Section IDs
- `#about`
- `#experience`
- `#projects`
- `#blog`
- `#contact`

---

## Projects to show

### Chase App Redesign
Created a high-fidelity prototype with flatter navigation, clearer interaction flow, and reduced interface complexity.

### Ponderly
Built a low-fidelity frontend foundation with reusable landing page systems that better communicate the platform's value proposition and engagement flow.

### DebtFree Dashboard *(placeholder)*
Debt payoff visualizer using avalanche and snowball methods. Replace or rename with real project.

### Credit Score Simulator *(placeholder)*
Interactive model showing how financial behaviors affect credit scores. Built for financial literacy workshops at UGA. Replace or rename with real project.

---

## Next build steps

### Immediate next task
Add the `#about` section between Hero and Experience.

**Purpose:** Explain who you are, what you're building toward, and why your projects connect across product, fintech, frontend, and systems thinking.

**The section should answer:**
- What kind of builder am I?
- What themes connect my work?
- Why do these projects matter?
- What direction am I moving toward?

**Constraint:** Keep it short. Not a biography — a positioning statement.

---

### Remaining priorities
1. Write and add `#about` section
2. Replace placeholder projects with real ones (Ponderly, etc.)
3. Add real email, LinkedIn, and GitHub URLs
4. Add resume PDF at `/assets/resume.pdf`
5. Add hero photo if desired
6. Fill blog with real articles or remove placeholder cards
7. Fill experience with accurate JPMC role details

---

## Stack
- Vanilla HTML + CSS (no framework)
- Google Fonts: Syne (headings), Inter (body)
- No build step — drop `index.html` and `style.css` into any static host
