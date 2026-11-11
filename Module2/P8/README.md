# P8: Sticky Navbar and Project-Card Overlay

## Aim
Use CSS positioning to keep navigation visible while scrolling and layer project details over a card image.

## Implementation
The finished page is [`index.html`](./index.html), with styles in [`styles.css`](./styles.css). `.site-header` uses `position: sticky`; each `.project-card` creates a positioning context, and `.overlay` is positioned over its artwork.

## Accessibility
The overlay appears on both `:hover` and `:focus-within`, so keyboard users can reach project links and read their descriptions. Open `index.html` and scroll or tab through the project links to try it.
