# Project API — Studio Ghibli

A vanilla JavaScript mini-app that explores REST API consumption and dynamic DOM manipulation, built with zero dependencies.

## Features

- **Ghibli Films** — fetches all Studio Ghibli movies from the [Ghibli API](https://ghibliapi.vercel.app) and renders them as cards on demand
- **Posts** — create and delete posts with an optional image (URL or local file upload)
- **Gallery** — add and remove images via URL or file upload
- **Responsive navbar** — dropdown menu with keyboard (`Escape`) and click-outside support

## Tech Stack

| Layer | Tech |
|-------|------|
| Markup | HTML5 |
| Styling | CSS3 (custom, no framework) |
| Logic | Vanilla JavaScript (ES2020+) |
| Data | [Studio Ghibli API](https://ghibliapi.vercel.app) |

## Getting Started

No build step required — just open `index.html` in a browser.

```bash
git clone https://github.com/aliyousfi-art/project-Api.git
cd project-Api
open index.html   # macOS
# or double-click index.html on Windows/Linux
```

## Project Structure

```
├── index.html   # App shell & layout
├── style.css    # All styles
└── script.js    # API calls, DOM rendering, event handling
```

## Preview

1. Click **API GENERATE** to load all Ghibli film cards
2. Use the **Posts** section to create a post (with optional image) and delete it
3. Use the **Gallery** section to build an image grid from URLs or local files
