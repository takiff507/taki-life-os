# Data Model

This document describes the main pieces of state used by Taki Life OS. The exact shape can evolve, but changes should stay easy to export, import, and inspect.

## Tasks

Tasks track a title, status, priority, optional due date, and timestamps.

## Habits

Habits track a name and a completion history keyed by date. Streaks are calculated from recent completion data.

## Focus Sessions

Focus sessions track duration, type, and completion time. The dashboard can summarize total focus minutes from these entries.

## Notes

Notes track title, body, and updated time. Search should use title and body text.

## Expenses

Expenses track label, amount, category, and date. Category totals are derived from the expense list.

## Settings

Settings store app preferences such as theme. Settings should never contain private secrets or API keys.
