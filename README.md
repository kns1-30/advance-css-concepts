# Advanced CSS Concepts

Two standalone exercises comparing different CSS layout techniques — same visual result, fundamentally different approaches.

| Folder | Technique |
|--------|-----------|
| `custom-grid-with-floats/` | Custom 12-column float-based grid built from scratch with `clearfix` |
| `display-grid/` | Equivalent layout rebuilt using native `display: grid` |

## Purpose

A side-by-side study of how legacy float grids compare to modern CSS Grid — useful for understanding why CSS Grid was introduced and what complexity it eliminates.

## Running

No build step required. Open `index.html` in either folder directly in the browser.

## Key Concepts Demonstrated

- Building a reusable float grid with percentage-based column widths and gutters
- Replacing float-based layout with `display: grid` and `grid-template-columns`
- Clearfix technique vs. implicit grid row creation
- Sass variables for grid configuration
