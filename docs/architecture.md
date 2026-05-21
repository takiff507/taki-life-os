# Architecture Overview

Taki Life OS is a static, local-first web app. It keeps the runtime simple so the project can be opened directly in a browser or hosted on GitHub Pages.

## Layers

- `index.html` defines the application shell and view containers.
- `styles.css` handles layout, responsive behavior, and the light/dark visual system.
- `script.js` owns state, rendering, interactions, and local persistence.

## State Model

The app keeps one structured state object for tasks, habits, focus sessions, notes, expenses, and settings. Updates are saved to `localStorage` after each user action.

## Rendering Model

Views are rendered from the current state. This keeps the app predictable: actions update state, state is saved, and the affected view is redrawn.

## Deployment

No build step is required. GitHub Pages can serve the repository root directly from the `main` branch.
