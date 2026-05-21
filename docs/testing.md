# Manual Testing Guide

Use this checklist before publishing changes.

## Startup

- Open `index.html` directly or through a static server.
- Confirm the dashboard loads without console errors.
- Toggle the theme and refresh the page to confirm the setting persists.

## Core Workflows

- Add a task from Quick Capture and confirm it appears on the dashboard.
- Add a task with priority and due date from the task board.
- Move a task between board columns.
- Add a habit and mark it complete for today.
- Start, pause, and reset the focus timer.
- Create, search, edit, and delete a note.
- Add an expense and confirm category totals update.

## Data Workflows

- Export a JSON backup from the Data tab.
- Import the exported JSON into a fresh browser profile or after reset.
- Confirm the restored state matches the exported state.

## Responsive Checks

- Test desktop width.
- Test tablet width.
- Test mobile width.
