# The Shady River Bard — Discography Portal & Concept Vault

Where the soil meets the signal. An interactive, data-driven portal for The Shady River Bard's 26 released concept albums, complete tracklists, streaming links, and an audience-driven voting vault for unreleased projects.

## Architecture

- **`index.html`**: Zero-dependency, responsive single-page portal built with modern semantic HTML5 and Tailwind CSS.
- **`data/albums.json`**: Master data registry containing metadata for:
  - 26 Released Albums (tracks, themes, genre, release year, streaming links, companion novellas)
  - 20 Vault Concepts (thematic pitches, track manifests, bespoke app links)
- **`data/albums-data.js`**: Offline-ready data wrapper ensuring the site works smoothly both as a local `file:///` path and on GitHub Pages with zero CORS restrictions.
- **`assets/covers/`**: Normalized high-resolution cover art for all 26 released records.
- **`assets/covers/vault/`**: Concept artwork and design documents for upcoming projects.

## Features

1. **Dual Perspective Selector**: Toggle seamlessly between *Released Discography (26)* and *The Vault / Incubator (20)*.
2. **Multi-Faceted Filtering & Live Search**: Filter instantly by themes (`#Poverty & Class`, `#Imperial Overstretch`, `#Digital Alienation`, `#Soil & Homestead`, etc.) or search across titles, tracks, and lyrics.
3. **Interactive Tracklist & Exploration Drawer**: Inspect full tracklists, song numbering, liner notes, and streaming platforms.
4. **Bespoke Deep-Dive Routing**: Links directly to bespoke interactive apps (such as [Sanity's Edge](https://tpatterson34.github.io/sanitys-edge/)).
5. **Audience Voting Mechanism**: Fans can vote on which unreleased concept album they want to see produced next. Votes are sent directly to `theshadyriverbard@gmail.com` via FormSubmit with zero server backend needed.
