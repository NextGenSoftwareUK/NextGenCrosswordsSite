# NextGen Crosswords

**Times · Sunday Times · The Sun**

NextGen Crosswords is a crossword puzzle platform and engine — the technology behind the official crosswords for The Times, The Sunday Times and The Sun. It is also the foundation for [Mindful Crosswords](../MindfulCrosswordsSite), the OASIS-integrated mindfulness puzzle app.

## Features

- Full crossword grid renderer with keyboard and touch support
- Clue panel with linked grid highlighting
- Timer, hints and reveal functionality
- Publisher-grade puzzle import (AcrossLite `.puz`, custom JSON)
- Mobile-first responsive layout
- Theming system for white-label deployments

## Deployments

| Publisher | URL |
|---|---|
| The Times | times crossword |
| The Sunday Times | sunday times crossword |
| The Sun | the sun crossword |
| Mindful Crosswords | OASIS Omniverse integration |

## Tech Stack

| Layer | Detail |
|---|---|
| Front-end | Single-file `index.html` — inline CSS + vanilla JS |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |
| Hosting | Static — any CDN or static host |

## Running Locally

```bash
npx serve .
# or
python -m http.server 8080
```
