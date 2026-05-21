# Accessibility Notes

Taki Life OS should stay usable with a keyboard, readable on small screens, and clear in both light and dark themes.

## Keyboard

- Interactive controls should be reachable with Tab.
- Buttons should use real `button` elements where possible.
- Forms should submit with Enter where that behavior is expected.

## Visual Design

- Text should keep strong contrast in light and dark themes.
- Click targets should stay large enough on mobile.
- Layout should avoid overlapping text at narrow widths.

## Content

- Button labels should describe the action.
- Empty states should explain what the user can do next.
- Error or reset actions should be easy to understand before data changes.

## Testing

Before release, test basic workflows with keyboard navigation and mobile width.
