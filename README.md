# Modern Theme Switcher

A sleek, accessible, and high-performance dark/light theme switcher built with pure HTML, CSS, and vanilla JavaScript. Designed following modern UI/UX standards, it ensures zero Flash of Unstyled Content (FOUC) and respects system color scheme preferences.

---

## Key Features

* **Zero FOUC (Flash of Unstyled Content):** Immediate theme evaluation via inline execution script before rendering the DOM.
* **OS Preference Auto-Detection:** Seamlessly syncs with the user's system setting (`prefers-color-scheme`) on first visit.
* **Persistent Preferences:** Remembers manual user toggles across sessions using `localStorage`.
* **Accessible (a11y):** Built with `aria-pressed` states, semantic tags, and keyboard focus-visible indicators.
* **Modern UI Design:** Uses CSS Variables (Design Tokens), responsive layouts, smooth color transitions, and scalable inline SVG icons.

---

## Tech Stack

* **HTML5** (Semantic layout, SVG icons)
* **CSS3** (CSS Variables, Flexbox, Media Queries, Transitions)
* **JavaScript** (Vanilla JS, LocalStorage API, MatchMedia API)

---

## Quick Start

1. **Clone or Download** the repository:
   ```bash
   git clone [https://github.com/your-username/theme-switcher.git](https://github.com/your-username/theme-switcher.git)