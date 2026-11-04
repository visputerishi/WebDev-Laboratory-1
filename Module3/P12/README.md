# P12: Portfolio Projects Grid with Advanced CSS Grid

## Aim
Arrange a set of portfolio projects in a responsive grid that adapts to available space.

## Implementation
The project-card grid is `.project-grid` in [`../../Module2/portfolio/styles.css`](../../Module2/portfolio/styles.css). It uses equal `minmax(0, 1fr)` columns on desktop and changes to two columns and then one column at smaller breakpoints. Each card is an independent semantic `article`.

## Try it
Resize the portfolio viewport and confirm the cards reflow without horizontal scrolling.
