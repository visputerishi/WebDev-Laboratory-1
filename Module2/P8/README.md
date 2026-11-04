# P8: Sticky Navbar and Project-Card Overlay

## Aim
Use CSS positioning to keep navigation visible while scrolling and layer project details over a card image.

## Implementation
In [`../portfolio/styles.css`](../portfolio/styles.css), `.site-header` uses `position: sticky`. Each `.project-card` establishes a positioning context, and its `.project-overlay` is positioned over the image and revealed on hover or keyboard focus.

## Accessibility
The overlay also appears on `:focus-within`, so keyboard users can reach project links and read their descriptions.
